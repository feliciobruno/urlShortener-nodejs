<h1 align="left">
  Encurtador de URL
</h1>

<h3 align="center">Objetivos do Projeto</h3>

<ol>
    <li>Construir uma API com NodeJS e Typescript.</li>
    <li>Gerar Hashes únicos para cada entrada.</li>
    <li>Conectar as entradas com os hashes gerados.</li>
</ol>

<hr>

<h3 align="center">Requisitos Básicos</h3>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ter instalado NodeJS.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Editor de texto da sua escolha.
</p>

<hr>

<h3 align="center">Parte 1: TypeScript</h3>
<h4 align="center">Linguagem Base</h4>

<h4 align="left">Typescript</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TypeScript é um superconjunto de JavaScript desenvolvido pela Microsoft que adiciona tipagem e alguns outros recursos a linguagem.
</p>

<hr>

<h3 align="center">Parte 2: MongoDB</h3>
<h4 align="center">Base de Dados</h4>

<h4 align="left">MongoDB</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MongoDB é um banco de dados NoSQL orientado à documentos.
</p>

<hr>

<h3 align="center">Iniciando o Projeto</h3>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MongoDB é um banco de dados NoSQL orientado à documentos.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pode ser utilizado instalado localmente ou em Cloud.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No projeto vai ser utilizado em Cloud.<br><br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Build a Cluster.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Free.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cluster Name: urlShortener-DIO
</p>

<pre>npm init</pre>
<pre>npm i typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint</pre>
<pre>npm i nodemon express cors</pre>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Criar a pasta: src<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Onde vai ter o código fonte.<br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dentro da pasta: src<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Criar o arquivo: index.ts
</p>

<hr>

- Gera TypeScriptt em JS.
<pre>npm run build:watch</pre>

- Restarta a API a cada mudança.
<pre>npm run dev</pre>

<hr>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Testando via GET no <a href="https://insomnia.rest/">Insomnia</a><br>
</p>

<pre>http://localhost:5000/test</pre>

``js
{
  "success": true
}
``