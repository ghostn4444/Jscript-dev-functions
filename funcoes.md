# 400 funções e métodos úteis em JScript

1. **`WScript.CreateObject()`** - Cria um objeto COM para interagir com o Windows.

2. **`WScript.Echo()`** - Exibe uma mensagem em uma janela de diálogo.

3. **`WScript.ScriptName`** - Retorna o nome do arquivo do script em execução.

4. **`String.fromCharCode()`** - Constrói uma string a partir de códigos ASCII.

5. **`String.charCodeAt()`** - Retorna o código ASCII de um caractere em uma posição específica.

6. **`String.split("")`** - Divide uma string em um array de caracteres.

7. **`String.reverse()`** - Inverte a ordem dos caracteres de uma string (implementado manualmente).

8. **`String.join()`** - Junta os elementos de um array em uma string.

9. **`String.substring()`** - Extrai uma parte de uma string.

10. **`String.slice()`** - Extrai uma seção de uma string e a retorna como uma nova string.

11. **`String.indexOf()`** - Retorna a posição da primeira ocorrência de uma substring.

12. **`String.lastIndexOf()`** - Retorna a posição da última ocorrência de uma substring.

13. **`String.replace()`** - Substitui uma substring por outra em uma string.

14. **`String.toLowerCase()`** - Converte todos os caracteres de uma string para minúsculas.

15. **`String.toUpperCase()`** - Converte todos os caracteres de uma string para maiúsculas.

16. **`String.trim()`** - Remove espaços em branco do início e do fim de uma string.

17. **`String.length`** - Retorna o comprimento de uma string.

18. **`String.split(",")`** - Divide uma string em um array usando vírgulas como delimitador.

19. **`Array.filter()`** - Cria um novo array com todos os elementos que passam em um teste específico.

20. **`Array.map()`** - Cria um novo array com os resultados da chamada de uma função em cada elemento do array.

21. **`Array.reduce()`** - Executa uma função redutora em cada elemento do array, resultando em um único valor.

22. **`Array.forEach()`** - Executa uma função para cada elemento do array.

23. **`Object.keys()`** - Retorna um array com os nomes das propriedades de um objeto.

24. **`Object.values()`** - Retorna um array com os valores das propriedades de um objeto.

25. **`Object.assign()`** - Copia valores de um ou mais objetos de origem para um objeto destino.

26. **`setTimeout()`** - Executa uma função após um atraso especificado em milissegundos.

27. **`clearTimeout()`** - Cancela uma chamada de `setTimeout()`.

28. **`setInterval()`** - Executa uma função repetidamente em intervalos especificados.

29. **`clearInterval()`** - Cancela uma chamada de `setInterval()`.

30. **`WScript.Sleep()`** - Pausa a execução do script por um número específico de milissegundos.

31. **`WScript.Shell`** - Cria um objeto para executar comandos do sistema.

32. **`Shell.Exec()`** - Executa um programa e retorna um objeto para interagir com o processo.

33. **`Shell.Run()`** - Executa um comando ou programa e pode aguardar sua conclusão.

34. **`Shell.ExpandEnvironmentStrings()`** - Expande uma variável de ambiente em uma string.

35. **`CreateObject("Scripting.FileSystemObject")`** - Cria um objeto para manipulação de arquivos e diretórios.

36. **`FileSystemObject.CreateTextFile()`** - Cria um novo arquivo de texto.

37. **`FileSystemObject.OpenTextFile()`** - Abre um arquivo de texto para leitura ou escrita.

38. **`FileSystemObject.DeleteFile()`** - Exclui um arquivo especificado.

39. **`FileSystemObject.GetFile()`** - Retorna um objeto de arquivo específico.

40. **`FileSystemObject.GetFolder()`** - Retorna um objeto de pasta específico.

41. **`FileSystemObject.FolderExists()`** - Verifica se uma pasta existe.

42. **`FileSystemObject.FileExists()`** - Verifica se um arquivo existe.

43. **`FileSystemObject.MoveFile()`** - Move um arquivo de um local para outro.

44. **`FileSystemObject.CopyFile()`** - Copia um arquivo de um local para outro.

45. **`FileSystemObject.CreateFolder()`** - Cria uma nova pasta.

46. **`WScript.Arguments`** - Acessa os argumentos passados para o script na linha de comando.

47. **`eval()`** - Executa uma string como código JScript.

48. **`String.match()`** - Executa uma busca por correspondências em uma string usando uma expressão regular.

49. **`String.search()`** - Executa uma busca de correspondência de uma expressão regular e retorna a posição.

50. **`RegExp()`** - Cria uma expressão regular para correspondência de padrões em strings.

51. **`WScript.Network`** - Cria um objeto para interagir com a rede.

52. **`Network.UserName`** - Retorna o nome do usuário conectado.

53. **`Network.ComputerName`** - Retorna o nome do computador.

54. **`String.concat()`** - Junta duas ou mais strings.

55. **`String.charAt()`** - Retorna o caractere em uma posição específica de uma string.

56. **`String.localeCompare()`** - Compara duas strings de acordo com a ordem local.

57. **`String.repeat()`** - Repete a string um número especificado de vezes.

58. **`Array.includes()`** - Determina se um array contém um determinado elemento.

59. **`Array.indexOf()`** - Retorna o primeiro índice em que um determinado elemento pode ser encontrado em um array.

60. **`Array.lastIndexOf()`** - Retorna o último índice em que um determinado elemento pode ser encontrado em um array.

61. **`Array.sort()`** - Ordena os elementos de um array.

62. **`Object.freeze()`** - Congela um objeto, impedindo alterações nas propriedades.

63. **`Object.seal()`** - Impede a adição de novas propriedades a um objeto.

64. **`JSON.stringify()`** - Converte um objeto JavaScript em uma string JSON.

65. **`JSON.parse()`** - Converte uma string JSON em um objeto JavaScript.

66. **`decodeURIComponent()`** - Decodifica uma string que foi codificada usando `encodeURIComponent()`.

67. **`encodeURIComponent()`** - Codifica um componente de URI.

68. **`decodeURI()`** - Decodifica uma string que foi codificada usando `encodeURI()`.

69. **`encodeURI()`** - Codifica uma URI.

70. **`String.charCodeAt()`** - Retorna o código ASCII de um caractere em uma posição específica.

71. **`Array.find()`** - Retorna o primeiro elemento do array que satisfaz a função de teste fornecida.

72. **`Array.findIndex()`** - Retorna o índice do primeiro elemento do array que satisfaz a função de teste fornecida.

73. **`Array.every()`** - Testa se todos os elementos do array passam na função de teste fornecida.

74. **`Array.some()`** - Testa se pelo menos um dos elementos do array passa na função de teste fornecida.

75. **`Array.concat()`** - Junta dois ou mais arrays.

76. **`Array.slice()`** - Retorna uma cópia de parte do array.

77. **`Array.splice()`** - Adiciona/remova elementos de um array.

78. **`String.includes()`** - Determina se uma string contém uma substring específica.

79. **`String.startsWith()`** - Determina se uma string começa com os caracteres de outra string.

80. **`String.endsWith()`** - Determina se uma string termina com os caracteres de outra string.

81. **`Array.fill()`** - Preenche todos os elementos de um array com um valor estático.

82. **`Object.entries()`** - Retorna um array dos pares chave-valor de um objeto.

83. **`Object.values()`** - Retorna um array dos valores de um objeto.

84. **`Object.keys()`** - Retorna um array das chaves de um objeto.

85. **`setImmediate()`** - Executa uma função assim que a pilha de execução estiver vazia.

86. **`clearImmediate()`** - Cancela a execução de uma função agendada por `setImmediate()`.

87. **`String.search()`** - Executa uma busca de correspondência de uma expressão regular.

88. **`String.replaceAll()`** - Substitui todas as ocorrências de uma substring em uma string.

89. **`String.padStart()`** - Preenche uma string com outra string até que a string tenha um determinado comprimento.

90. **`String.padEnd()`** - Preenche uma string com outra string até que a string tenha um determinado comprimento.

91. **`String.toLocaleLowerCase()`** - Converte todos os caracteres de uma string para minúsculas de acordo com a localidade.

92. **`String.toLocaleUpperCase()`** - Converte todos os caracteres de uma string para maiúsculas de acordo com a localidade.

93. **`WScript.Shell.Environment()`** - Acessa as variáveis de ambiente.

94. **`WScript.Network.EnumComputers()`** - Enumera computadores na rede.

95. **`WScript.Shell.Popup()`** - Exibe uma janela pop-up com uma mensagem.

96. **`WScript.Shell.RegRead()`** - Lê um valor do registro do Windows.

97. **`WScript.Shell.RegWrite()`** - Escreve um valor no registro do Windows.

98. **`WScript.Shell.RegDelete()`** - Exclui um valor do registro do Windows.

99. **`WScript.Shell.RunCommand()`** - Executa um comando no shell e espera que ele termine.

100. **`String.toString()`** - Converte um objeto em uma string.

101. **`Array.push()`** - Adiciona um ou mais elementos ao final de um array.

102. **`Array.pop()`** - Remove o último elemento de um array.

103. **`Array.unshift()`** - Adiciona um ou mais elementos ao início de um array.

104. **`Array.shift()`** - Remove o primeiro elemento de um array.

105. **`Array.reverse()`** - Inverte a ordem dos elementos de um array.

106. **`Array.sort()`** - Ordena os elementos de um array.

107. **`String.split(" ")`** - Divide uma string em um array usando espaços como delimitador.

108. **`String.includes()`** - Verifica se uma string contém outra string.

109. **`String.endsWith()`** - Verifica se uma string termina com uma substring específica.

110. **`String.startsWith()`** - Verifica se uma string começa com uma substring específica.

111. **`String.toString()`** - Converte o valor de um objeto para uma string.

112. **`String.valueOf()`** - Retorna uma string que representa o valor do objeto.

113. **`Array.copyWithin()`** - Copia parte do array para outro local no mesmo array.

114. **`Array.entries()`** - Retorna um novo objeto Array Iterator que contém os pares chave-valor.

115. **`Array.keys()`** - Retorna um novo objeto Array Iterator que contém as chaves de um array.

116. **`Array.values()`** - Retorna um novo objeto Array Iterator que contém os valores de um array.

117. **`Object.getOwnPropertyNames()`** - Retorna todas as propriedades de um objeto.

118. **`Object.getOwnPropertyDescriptor()`** - Retorna uma descrição de uma propriedade específica de um objeto.

119. **`Object.create()`** - Cria um novo objeto, usando um objeto existente como protótipo.

120. **`Object.defineProperty()`** - Define uma nova propriedade diretamente em um objeto.

121. **`Object.defineProperties()`** - Define várias propriedades em um objeto.

122. **`Object.is()`** - Compara dois valores para verificar se são iguais.

123. **`Object.assign()`** - Copia as propriedades de um ou mais objetos para um objeto alvo.

124. **`Object.prototype.hasOwnProperty()`** - Retorna um booleano que indica se o objeto possui a propriedade especificada.

125. **`String.localeCompare()`** - Compara duas strings de acordo com a ordem local.

126. **`Array.fill()`** - Preenche todos os elementos de um array com um valor estático.

127. **`Array.flat()`** - Cria um novo array com todos os elementos de sub-array concatenados.

128. **`Array.flatMap()`** - Primeiro mapeia cada elemento usando uma função, depois achata o resultado em um novo array.

129. **`Array.find()`** - Retorna o primeiro elemento que satisfaz a função de teste fornecida.

130. **`Array.findIndex()`** - Retorna o índice do primeiro elemento que satisfaz a função de teste fornecida.

131. **`Array.every()`** - Testa se todos os elementos passam pela função de teste fornecida.

132. **`Array.some()`** - Testa se pelo menos um dos elementos passa pela função de teste fornecida.

133. **`Array.forEach()`** - Executa uma função para cada elemento do array.

134. **`Array.reduceRight()`** - Executa uma função redutora em cada elemento do array, da direita para a esquerda.

135. **`Array.slice()`** - Retorna uma cópia de uma parte do array.

136. **`Array.splice()`** - Altera o conteúdo de um array, adicionando novos elementos enquanto remove elementos antigos.

137. **`Array.concat()`** - Junta dois ou mais arrays.

138. **`Array.indexOf()`** - Retorna o primeiro índice em que um determinado elemento pode ser encontrado em um array.

139. **`Array.lastIndexOf()`** - Retorna o último índice em que um determinado elemento pode ser encontrado em um array.

140. **`String.search()`** - Executa uma busca de correspondência de uma expressão regular e retorna a posição.

141. **`String.replace()`** - Substitui uma substring por outra em uma string.

142. **`String.replaceAll()`** - Substitui todas as ocorrências de uma substring em uma string.

143. **`String.match()`** - Executa uma busca por correspondências em uma string usando uma expressão regular.

144. **`String.split(",")`** - Divide uma string em um array usando vírgulas como delimitador.

145. **`String.repeat()`** - Repete uma string um número especificado de vezes.

146. **`String.charAt()`** - Retorna o caractere em uma posição específica de uma string.

147. **`String.toLowerCase()`** - Converte todos os caracteres de uma string para minúsculas.

148. **`String.toUpperCase()`** - Converte todos os caracteres de uma string para maiúsculas.

149. **`String.trim()`** - Remove espaços em branco do início e do fim de uma string.

150. **`String.length`** - Retorna o comprimento de uma string.

151. **`WScript.Shell.Environment()`** - Acessa as variáveis de ambiente do sistema.

152. **`WScript.Network.EnumComputers()`** - Enumera computadores disponíveis na rede.

153. **`WScript.Shell.Popup()`** - Exibe uma janela pop-up com uma mensagem e botões.

154. **`WScript.Sleep()`** - Pausa a execução do script por um número específico de milissegundos.

155. **`WScript.Arguments`** - Acessa os argumentos passados para o script na linha de comando.

156. **`eval()`** - Executa uma string como código JScript.

157. **`decodeURIComponent()`** - Decodifica um componente de URI.

158. **`encodeURIComponent()`** - Codifica um componente de URI.

159. **`decodeURI()`** - Decodifica uma URI.

160. **`encodeURI()`** - Codifica uma URI.

161. **`Array.prototype.keys()`** - Retorna um novo Array Iterator que contém as chaves de um array.

162. **`Array.prototype.values()`** - Retorna um novo Array Iterator que contém os valores de um array.

163. **`Array.prototype.entries()`** - Retorna um novo Array Iterator que contém os pares chave-valor.

164. **`Array.prototype.fill()`** - Preenche todos os elementos de um array com um valor estático.

165. **`Array.prototype.every()`** - Testa se todos os elementos do array passam na função de teste fornecida.

166. **`Array.prototype.some()`** - Testa se pelo menos um dos elementos do array passa na função de teste fornecida.

167. **`Array.prototype.filter()`** - Cria um novo array com todos os elementos que passam no teste fornecido.

168. **`Array.prototype.forEach()`** - Executa uma função para cada elemento do array.

169. **`Array.prototype.map()`** - Cria um novo array com os resultados da chamada de uma função em cada elemento do array.

170. **`Array.prototype.reduce()`** - Executa uma função redutora em cada elemento do array, resultando em um único valor.

171. **`Array.prototype.reduceRight()`** - Executa uma função redutora em cada elemento do array, da direita para a esquerda.

172. **`Array.prototype.reverse()`** - Inverte a ordem dos elementos de um array.

173. **`Array.prototype.sort()`** - Ordena os elementos de um array.

174. **`Object.freeze()`** - Congela um objeto, impedindo alterações nas propriedades.

175. **`Object.seal()`** - Impede a adição de novas propriedades a um objeto.

176. **`Object.assign()`** - Copia as propriedades de um ou mais objetos para um objeto alvo.

177. **`Object.create()`** - Cria um novo objeto, usando um objeto existente como protótipo.

178. **`Object.getOwnPropertyNames()`** - Retorna todas as propriedades de um objeto.

179. **`Object.getOwnPropertyDescriptor()`** - Retorna uma descrição de uma propriedade específica de um objeto.

180. **`Object.prototype.hasOwnProperty()`** - Retorna um booleano que indica se o objeto possui a propriedade especificada.

181. **`Object.prototype.toString()`** - Retorna uma string representando o objeto.

182. **`Object.prototype.valueOf()`** - Retorna o valor primitivo do objeto.

183. **`Object.keys()`** - Retorna um array das chaves de um objeto.

184. **`Object.values()`** - Retorna um array dos valores de um objeto.

185. **`String.localeCompare()`** - Compara duas strings de acordo com a ordem local.

186. **`WScript.Shell.RegRead()`** - Lê um valor do registro do Windows.

187. **`WScript.Shell.RegWrite()`** - Escreve um valor no registro do Windows.

188. **`WScript.Shell.RegDelete()`** - Exclui um valor do registro do Windows.

189. **`WScript.Shell.RunCommand()`** - Executa um comando no shell e espera que ele termine.

190. **`WScript.Shell.ExpandEnvironmentStrings()`** - Expande as variáveis de ambiente em uma string.

191. **`WScript.Network.ComputerName`** - Retorna o nome do computador.

192. **`WScript.Network.UserName`** - Retorna o nome do usuário conectado.

193. **`WScript.Network.EnumNetworkConnections()`** - Enumera as conexões de rede.

194. **`WScript.Shell.AppActivate()`** - Ativa uma janela de aplicativo.

195. **`WScript.Shell.SendKeys()`** - Envia teclas para a janela ativa.

196. **`WScript.Shell.Popup()`** - Exibe uma mensagem em uma caixa de diálogo.

197. **`WScript.Shell.CreateShortcut()`** - Cria um atalho para um arquivo ou pasta.

198. **`WScript.Shell.Run()`** - Executa um comando ou programa.

199. **`WScript.Shell.Environment()`** - Acessa as variáveis de ambiente.

200. **`WScript.Shell.CurrentDirectory`** - Retorna o diretório de trabalho atual.

201. **`WScript.Shell.Exec()`** - Executa um comando e retorna um objeto para interagir com o processo.

202. **`WScript.Sleep()`** - Pausa a execução do script por um número específico de milissegundos.

203. **`WScript.Arguments`** - Acessa os argumentos passados para o script na linha de comando.

204. **`WScript.ScriptFullName`** - Retorna o caminho completo do script em execução.

205. **`WScript.Version`** - Retorna a versão do Windows Script Host.

206. **`WScript.Quit()`** - Encerra a execução do script.

207. **`WScript.GetObject()`** - Retorna uma referência a um objeto COM.

208. **`WScript.SetTimeout()`** - Define um atraso para a execução de uma função.

209. **`WScript.GetScriptTimeout()`** - Retorna o tempo limite de execução do script.

210. **`WScript.SetScriptTimeout()`** - Define o tempo limite de execução do script.

211. **`WScript.GetObject()`** - Obtém um objeto existente a partir de um identificador.

212. **`WScript.ScriptTimeout`** - Obtém ou define o tempo limite de execução do script.

213. **`String.charAt()`** - Retorna o caractere em uma posição específica de uma string.

214. **`String.indexOf()`** - Retorna a posição da primeira ocorrência de uma substring.

215. **`String.lastIndexOf()`** - Retorna a posição da última ocorrência de uma substring.

216. **`String.includes()`** - Determina se uma string contém outra string.

217. **`String.startsWith()`** - Determina se uma string começa com uma substring específica.

218. **`String.endsWith()`** - Determina se uma string termina com uma substring específica.

219. **`String.match()`** - Executa uma busca por correspondências em uma string usando uma expressão regular.

220. **`String.search()`** - Executa uma busca de correspondência de uma expressão regular.

221. **`String.replace()`** - Substitui uma substring por outra em uma string.

222. **`String.replaceAll()`** - Substitui todas as ocorrências de uma substring em uma string.

223. **`String.trim()`** - Remove espaços em branco do início e do fim de uma string.

224. **`String.toLowerCase()`** - Converte todos os caracteres de uma string para minúsculas.

225. **`String.toUpperCase()`** - Converte todos os caracteres de uma string para maiúsculas.

226. **`String.split(",")`** - Divide uma string em um array usando vírgulas como delimitador.

227. **`String.substring()`** - Extrai uma parte de uma string.

228. **`String.slice()`** - Extrai uma seção de uma string e a retorna como uma nova string.

229. **`String.localeCompare()`** - Compara duas strings de acordo com a ordem local.

230. **`WScript.Shell.Popup()`** - Exibe uma mensagem em uma caixa de diálogo.

231. **`WScript.Shell.Run()`** - Executa um comando ou programa.

232. **`WScript.Shell.CreateShortcut()`** - Cria um atalho para um arquivo ou pasta.

233. **`WScript.Sleep()`** - Pausa a execução do script por um número específico de milissegundos.

234. **`WScript.Arguments`** - Acessa os argumentos passados para o script na linha de comando.

235. **`eval()`** - Executa uma string como código JScript.

236. **`decodeURIComponent()`** - Decodifica um componente de URI.

237. **`encodeURIComponent()`** - Codifica um componente de URI.

238. **`decodeURI()`** - Decodifica uma URI.

239. **`encodeURI()`** - Codifica uma URI.

240. **`Array.prototype.slice()`** - Retorna uma cópia de parte do array.

241. **`Array.prototype.splice()`** - Adiciona/remova elementos de um array.

242. **`Array.prototype.concat()`** - Junta dois ou mais arrays.

243. **`Array.prototype.indexOf()`** - Retorna o primeiro índice em que um determinado elemento pode ser encontrado em um array.

244. **`Array.prototype.lastIndexOf()`** - Retorna o último índice em que um determinado elemento pode ser encontrado em um array.

245. **`Array.prototype.sort()`** - Ordena os elementos de um array.

246. **`Array.prototype.reverse()`** - Inverte a ordem dos elementos de um array.

247. **`Array.prototype.every()`** - Testa se todos os elementos do array passam na função de teste fornecida.

248. **`Array.prototype.some()`** - Testa se pelo menos um dos elementos passa na função de teste fornecida.

249. **`Array.prototype.filter()`** - Cria um novo array com todos os elementos que passam no teste fornecido.

250. **`Array.prototype.forEach()`** - Executa uma função para cada elemento do array.

251. **`Array.prototype.map()`** - Cria um novo array com os resultados da chamada de uma função em cada elemento do array.

252. **`Array.prototype.reduce()`** - Executa uma função redutora em cada elemento do array, resultando em um único valor.

253. **`Array.prototype.flat()`** - Cria um novo array com todos os elementos de sub-array concatenados.

254. **`Array.prototype.flatMap()`** - Primeiro mapeia cada elemento usando uma função, depois achata o resultado em um novo array.

255. **`Object.prototype.hasOwnProperty()`** - Retorna um booleano que indica se o objeto possui a propriedade especificada.

256. **`Object.prototype.toString()`** - Retorna uma string representando o objeto.

257. **`Object.prototype.valueOf()`** - Retorna o valor primitivo do objeto.

258. **`Object.keys()`** - Retorna um array das chaves de um objeto.

259. **`Object.values()`** - Retorna um array dos valores de um objeto.

260. **`Object.entries()`** - Retorna um array dos pares chave-valor de um objeto.

261. **`Object.freeze()`** - Congela um objeto, impedindo alterações nas propriedades.

262. **`Object.seal()`** - Impede a adição de novas propriedades a um objeto.

263. **`Object.assign()`** - Copia as propriedades de um ou mais objetos para um objeto alvo.

264. **`Object.create()`** - Cria um novo objeto, usando um objeto existente como protótipo.

265. **`Object.getOwnPropertyNames()`** - Retorna todas as propriedades de um objeto.

266. **`Object.getOwnPropertyDescriptor()`** - Retorna uma descrição de uma propriedade específica de um objeto.

267. **`setTimeout()`** - Executa uma função após um atraso especificado em milissegundos.

268. **`clearTimeout()`** - Cancela uma chamada de `setTimeout()`.

269. **`setInterval()`** - Executa uma função repetidamente em intervalos especificados.

270. **`clearInterval()`** - Cancela uma chamada de `setInterval()`.

271. **`console.log()`** - Exibe uma mensagem no console.

272. **`console.error()`** - Exibe uma mensagem de erro no console.

273. **`console.warn()`** - Exibe uma mensagem de aviso no console.

274. **`console.info()`** - Exibe uma mensagem informativa no console.

275. **`console.table()`** - Exibe dados tabulares como uma tabela no console.

276. **`console.time()`** - Inicia um temporizador para medir o tempo.

277. **`console.timeEnd()`** - Para o temporizador e exibe o tempo decorrido.

278. **`window.alert()`** - Exibe uma caixa de diálogo de alerta com uma mensagem.

279. **`window.confirm()`** - Exibe uma caixa de diálogo de confirmação.

280. **`window.prompt()`** - Exibe uma caixa de diálogo que solicita entrada do usuário.

281. **`window.open()`** - Abre uma nova janela ou guia do navegador.

282. **`window.close()`** - Fecha a janela atual.

283. **`window.setTimeout()`** - Define um atraso antes da execução de uma função.

284. **`window.clearTimeout()`** - Cancela uma chamada de `setTimeout()`.

285. **`window.setInterval()`** - Executa uma função repetidamente em intervalos especificados.

286. **`window.clearInterval()`** - Cancela uma chamada de `setInterval()`.

287. **`document.getElementById()`** - Retorna o elemento com o ID especificado.

288. **`document.querySelector()`** - Retorna o primeiro elemento que corresponde ao seletor CSS especificado.

289. **`document.querySelectorAll()`** - Retorna todos os elementos que correspondem ao seletor CSS especificado.

290. **`document.createElement()`** - Cria um novo elemento HTML.

291. **`document.appendChild()`** - Adiciona um novo nó ao final da lista de filhos de um nó.

292. **`document.removeChild()`** - Remove um filho específico de um nó.

293. **`document.replaceChild()`** - Substitui um filho existente por um novo nó.

294. **`document.write()`** - Escreve uma string de texto para o documento.

295. **`document.open()`** - Abre um documento para escrita.

296. **`document.close()`** - Fecha um documento aberto para escrita.

297. **`document.body`** - Retorna o corpo do documento.

298. **`document.title`** - Retorna ou define o título do documento.

299. **`document.location`** - Retorna a URL do documento atual.

300. **`document.referrer`** - Retorna o URL do documento que levou à página atual.

301. **`document.cookie`** - Retorna ou define os cookies associados ao documento.

302. **`navigator.userAgent`** - Retorna a string que identifica o navegador.

303. **`navigator.geolocation.getCurrentPosition()`** - Obtém a posição geográfica do usuário.

304. **`navigator.mediaDevices.getUserMedia()`** - Solicita acesso aos dispositivos de mídia.

305. **`localStorage.setItem()`** - Armazena um item no armazenamento local.

306. **`localStorage.getItem()`** - Recupera um item do armazenamento local.

307. **`localStorage.removeItem()`** - Remove um item do armazenamento local.

308. **`localStorage.clear()`** - Remove todos os itens do armazenamento local.

309. **`sessionStorage.setItem()`** - Armazena um item na sessão do armazenamento.

310. **`sessionStorage.getItem()`** - Recupera um item da sessão do armazenamento.

311. **`sessionStorage.removeItem()`** - Remove um item da sessão do armazenamento.

312. **`sessionStorage.clear()`** - Remove todos os itens da sessão do armazenamento.

313. **`fetch()`** - Faz uma solicitação de rede e retorna uma promessa.

314. **`Promise.all()`** - Retorna uma promessa que é resolvida quando todas as promessas são resolvidas.

315. **`Promise.race()`** - Retorna uma promessa que é resolvida ou rejeitada assim que uma das promessas for resolvida ou rejeitada.

316. **`Promise.resolve()`** - Retorna uma promessa resolvida com um valor.

317. **`Promise.reject()`** - Retorna uma promessa rejeitada com um motivo.

318. **`async`** - Declara uma função assíncrona.

319. **`await`** - Espera por uma promessa para ser resolvida.

320. **`try...catch`** - Trata exceções em código assíncrono.

321. **`finally`** - Executa código após o bloco `try` e `catch`, independentemente de uma exceção ter ocorrido.

322. **`JSON.stringify()`** - Converte um objeto JavaScript em uma string JSON.

323. **`JSON.parse()`** - Converte uma string JSON em um objeto JavaScript.

324. **`Array.isArray()`** - Determina se o valor passado é um array.

325. **`Object.prototype.toString.call()`** - Retorna a string de tipo de um objeto.

326. **`Symbol()`** - Cria um novo símbolo, um identificador único e imutável.

327. **`WeakMap()`** - Cria um objeto `WeakMap` que permite que objetos sejam usados como chaves.

328. **`WeakSet()`** - Cria um objeto `WeakSet` que permite que objetos sejam armazenados sem impedir sua coleta de lixo.

329. **`Map()`** - Cria um objeto `Map`, uma coleção de pares chave-valor.

330. **`Set()`** - Cria um objeto `Set`, uma coleção de valores únicos.

331. **`Math.random()`** - Retorna um número pseudoaleatório entre 0 e 1.

332. **`Math.floor()`** - Arredonda um número para baixo até o inteiro mais próximo.

333. **`Math.ceil()`** - Arredonda um número para cima até o inteiro mais próximo.

334. **`Math.round()`** - Arredonda um número para o inteiro mais próximo.

335. **`Math.max()`** - Retorna o maior número entre os valores fornecidos.

336. **`Math.min()`** - Retorna o menor número entre os valores fornecidos.

337. **`Math.abs()`** - Retorna o valor absoluto de um número.

338. **`Math.sqrt()`** - Retorna a raiz quadrada de um número.

339. **`Math.pow()`** - Retorna a base elevada a um expoente.

340. **`Math.sin()`** - Retorna o seno de um ângulo.

341. **`Math.cos()`** - Retorna o cosseno de um ângulo.

342. **`Math.tan()`** - Retorna a tangente de um ângulo.

343. **`Math.log()`** - Retorna o logaritmo natural de um número.

344. **`Math.exp()`** - Retorna o valor de `e` elevado a um número.

345. **`Math.PI`** - Uma constante que representa o valor de π (Pi).

346. **`Math.E`** - Uma constante que representa o valor de `e` (base dos logaritmos naturais).

347. **`Math.random()`** - Retorna um número pseudoaleatório entre 0 e 1.

348. **`Date.now()`** - Retorna a data e hora atuais em milissegundos desde 1 de janeiro de 1970.

349. **`Date.parse()`** - Analisa uma string de data e retorna o número de milissegundos.

350. **`Date.UTC()`** - Retorna o número de milissegundos desde 1 de janeiro de 1970, em UTC.

351. **`Date.getDate()`** - Retorna o dia do mês para uma data.

352. **`Date.getDay()`** - Retorna o dia da semana para uma data.

353. **`Date.getMonth()`** - Retorna o mês para uma data (0-11).

354. **`Date.getFullYear()`** - Retorna o ano para uma data.

355. **`Date.getHours()`** - Retorna a hora para uma data.

356. **`Date.getMinutes()`** - Retorna os minutos para uma data.

357. **`Date.getSeconds()`** - Retorna os segundos para uma data.

358. **`Date.getMilliseconds()`** - Retorna os milissegundos para uma data.

359. **`Date.setDate()`** - Define o dia do mês para uma data.

360. **`Date.setMonth()`** - Define o mês para uma data.

361. **`Date.setFullYear()`** - Define o ano para uma data.

362. **`Date.setHours()`** - Define a hora para uma data.

363. **`Date.setMinutes()`** - Define os minutos para uma data.

364. **`Date.setSeconds()`** - Define os segundos para uma data.

365. **`Date.setMilliseconds()`** - Define os milissegundos para uma data.

366. **`Date.toISOString()`** - Retorna a data como uma string no formato ISO 8601.

367. **`Date.toString()`** - Retorna uma string representando a data.

368. **`Date.toLocaleString()`** - Retorna uma string representando a data em uma string local.

369. **`Date.toLocaleDateString()`** - Retorna a parte da data em uma string local.

370. **`Date.toLocaleTimeString()`** - Retorna a parte da hora em uma string local.

371. **`JSON.stringify()`** - Converte um objeto JavaScript em uma string JSON.

372. **`JSON.parse()`** - Converte uma string JSON em um objeto JavaScript.

373. **`window.localStorage`** - Propriedade que permite acessar o armazenamento local.

374. **`window.sessionStorage`** - Propriedade que permite acessar o armazenamento da sessão.

375. **`window.history`** - Propriedade que permite acessar o histórico do navegador.

376. **`window.navigator`** - Propriedade que fornece informações sobre o navegador.

377. **`window.screen`** - Propriedade que fornece informações sobre a tela do usuário.

378. **`window.document`** - Propriedade que representa o documento carregado na janela.

379. **`window.location`** - Propriedade que representa a URL da janela atual.

380. **`window.top`** - Propriedade que retorna a janela de nível superior.

381. **`window.parent`** - Propriedade que retorna a janela pai da janela atual.

382. **`window.self`** - Propriedade que retorna uma referência à janela atual.

383. **`window.opener`** - Propriedade que retorna a janela que abriu a janela atual.

384. **`window.frames`** - Propriedade que retorna uma coleção de todas as frames da janela.

385. **`window.alert()`** - Exibe um alerta ao usuário.

386. **`window.confirm()`** - Exibe uma caixa de diálogo de confirmação.

387. **`window.prompt()`** - Exibe uma caixa de diálogo de entrada.

388. **`window.open()`** - Abre uma nova janela ou aba.

389. **`window.close()`** - Fecha a janela atual.

390. **`window.focus()`** - Define o foco na janela atual.

391. **`window.blur()`** - Remove o foco da janela atual.

392. **`window.resizeTo()`** - Redimensiona a janela atual.

393. **`window.moveTo()`** - Move a janela atual para uma nova posição.

394. **`window.print()`** - Abre a caixa de diálogo de impressão.

395. **`window.setTimeout()`** - Define um atraso para a execução de uma função.

396. **`window.clearTimeout()`** - Cancela uma chamada de `setTimeout()`.

397. **`window.setInterval()`** - Executa uma função repetidamente em intervalos especificados.

398. **`window.clearInterval()`** - Cancela uma chamada de `setInterval()`.

399. **`window.requestAnimationFrame()`** - Solicita ao navegador que chame uma função para o próximo quadro de animação.

400. **`window.cancelAnimationFrame()`** - Cancela uma chamada a `requestAnimationFrame()`.

### Essas funções cobrem uma ampla gama de funcionalidades no JScript, desde manipulação de strings e arrays até interações com o DOM e APIs do navegador.
