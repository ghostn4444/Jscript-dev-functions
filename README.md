# Documentação do Projeto JScript Para Malwers

### Descrição
Este projeto é uma coleção de scripts em JScript para automação de tarefas no ambiente Windows, como manipulação de arquivos, execução de comandos do sistema e automação de aplicativos.

### Pré-requisitos
Windows com suporte a JScript (geralmente disponível em todas as versões do Windows).
Acesso ao console de comandos do Windows.

### Instalação
Os scripts podem ser executados diretamente no ambiente de linha de comando do Windows ou através de um arquivo <code>js</code>. Para criar um arquivo, use um editor de texto e salve-o com a extensão <code>js</code>.

<br/>

<h2>Programar malwares com JScript pode apresentar algumas vantagens, especialmente na perspectiva de um hacker.</h2>

### 1. Compatibilidade com Windows
JScript é suportado nativamente no Windows, o que significa que muitos sistemas já têm o ambiente necessário para executar scripts JScript. Isso facilita a disseminação de malwares, pois não requer instalação de software adicional.

### 2. Execução via Scripts
Malwares escritos em JScript podem ser executados através de scripts simples, tornando-os fáceis de distribuir e ocultar. Eles podem ser enviados como anexos de e-mail ou incluídos em páginas web, evitando a necessidade de criar um executável.

### 3. Manipulação do Sistema
JScript pode interagir com o sistema operacional através de ActiveX, permitindo acesso a funções do sistema, como manipulação de arquivos, execução de comandos, e até controle de processos.

### 4. Menor Detecção
Scripts JScript podem ser menos detectáveis por algumas soluções de segurança, especialmente se forem ofuscados ou integrados em outros arquivos. A execução em um ambiente de script pode levantar menos suspeitas do que um executável típico.

### 5. Automação e Engenharia Social
JScript pode ser utilizado para criar scripts que automatizam ações maliciosas, como download de payloads, coleta de informações do sistema e engenharia social, fazendo uso de janelas de alerta e mensagens que enganam os usuários.

### 6. Facilidade de Uso
A sintaxe do JScript é similar ao JavaScript, o que pode ser mais acessível para programadores com experiência em desenvolvimento web. Isso pode permitir que hackers com conhecimentos básicos consigam desenvolver malwares rapidamente.

### 7. Cross-Site Scripting (XSS)
JScript pode ser utilizado em ataques de XSS em aplicações web, explorando vulnerabilidades em sites para executar código no navegador da vítima, o que pode levar ao roubo de dados ou controle da sessão.


<br/>

## Execução de Scripts JScript
Para executar um script JScript, use o comando cscript no console do Windows:

```cmd
cscript caminho\para\seu\script.js
```

<br/>

# Funções Principais

### 1. FileExists(filePath)
Verifica se um arquivo existe em um caminho especificado.

* Parâmetros: filePath (string): O caminho completo do arquivo.

* Retorna: (boolean): true se o arquivo existir, false caso contrário.

Exemplo:

```javascript
function FileExists(filePath) {
    var fso = new ActiveXObject("Scripting.FileSystemObject");
    return fso.FileExists(filePath);
}

if (FileExists("C:\\teste.txt")) {
    WScript.Echo("O arquivo existe.");
} else {
    WScript.Echo("O arquivo não existe.");
}
```

<br/>

### 2. CreateFile(filePath)
Cria um novo arquivo no caminho especificado.

* Parâmetros: filePath (string): O caminho completo do arquivo a ser criado.

Exemplo:

```javascript
function CreateFile(filePath) {
    var fso = new ActiveXObject("Scripting.FileSystemObject");
    var file = fso.CreateTextFile(filePath, true);
    file.WriteLine("Este é um arquivo criado por JScript.");
    file.Close();
}

CreateFile("C:\\novoArquivo.txt");

```

<br/>

### 3. RunCommand(command)
Executa um comando do sistema.

Parâmetros: command (string): O comando a ser executado.

Exemplo:

```javascript
function RunCommand(command) {
    var shell = new ActiveXObject("WScript.Shell");
    shell.Run(command);
}

RunCommand("notepad.exe");
```
