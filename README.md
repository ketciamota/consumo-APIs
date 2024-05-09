# consumo-APIs
Repositório para as demonstrações e aprendizado sobre o consumo de APIs

As APIs possuem alguns elemntos que servem à sua utilização:

-**Ponto de /api/v2entrada**: é o endereço do serviço hospedado e que pode ser acessado
através de um navegador ou uma ferramenta de consumo de APIs.
Exemplo: <https://dadosabertos.camara.leg.br/api/v2>.

-**Recursos**: são serviços de dados disponíveis para consumo.
Exemplo: <https://dadosabertos.camara.leg.br/v2/deputados>.

-**Parâmetros**: são informações ou filtros que servem para enviar dados
da consulta ou para serem processados pela API. Os parâmetros podem ser 
passados para a API através da URL ou no corpo (body) da requisição.
Exemplo: ?nome=bebeto -> <https://dadosbaertos.camara.leg.br/api/v2/deputados?nome=bebeto>.

-**Métodos**: são os modos de consumo de uma API,que podem ser:
-POST: inserção (CREATE)
-GET: consulta/leitura (READ)
-UPDATE: atualização (UPDATE)
-DELETE: deleção (DELETE)

Para este projeto vamos usar o Node.js e o NPM (Node Package Manager):
- Node.js v20.13.0 LTS -> Long Term Suport (versão estável)
- NPX -> Node Package eXecuter(Executor de pacote do Node)

TO-DO(documentar):
# Instalação e uso do Json Server: <https://github.com/typicode/json-server>
Instalação do Node.js na versão atual

# Criação do .gitignore

~~~bash
git add .gitignore
~~~

- Utilização dos arquivos package
- Criação do script "start" no package.json
- Observações em relação ao uso do JSON vs. JSON: <https://github.com/json5/json5>
- Instalação das extensões para formatação de arquivo .json5

- Chamada do script start com NPM ao invés do NPX
Executar no terminal como se fosse o gerenciador que chama o executor npx
~~~bash
npm start
~~~

- O que é o Chocolatey (e porque não instalá-lo agora)

