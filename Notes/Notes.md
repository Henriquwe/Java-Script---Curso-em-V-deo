# Java Script - Curso em Vídeo - Anotações persistentes

- Surgiu como uma tecnologia para CLIENTES, porém atualmente funciona também para SERVIDORES.
- É uma tecnologia CLIENT SIDE a priori.
- Uma tecnologia que provê muitas funções.
- NodeJS é o principal envolvido no porte do Java Script para o lado do SERVIDOR.
- Principais tecnologias derivadas do JS: JQuery, Angular, React, Electron, Ionic.

## Ex 002 -> Tratamento de dados - Curso JavaScript #06

- Conversão de Tipos das variáveis através da função Number.parseInt ou n.toString()
- Uso das funções toLowerCase() e toUpperCase()
- Uso da função document.write para inscrição direta no documento HTML
- Uso da função toFixed(n) onde N é o número de casas decimais a serem rearranjadas.
- Uso da função replace(".", ",") onde se substitui o valor . e , entre as aspas para os parâmetros que devem ser modificados.

## Ex 003 -> Introdução ao DOM - Curso JavaScript #09

- DOM -> Document Object Model.
- Árvore DOM, composta por:
- (1) Window
- (2) Location
- (2) Document
    (2.1) HTML
        (2.2) HEAD
            (2.3) META
            (2.3) TITLE
        (2.2) BODY
            (2.3) H1
            (2.3) P
            (2.3) 2° P
                (2.4) STRONG
            (2.3) DIV
- (2) History
- Os elementos acima podem ser acessados por:
- Marca:
  - getElementsByTagName()
  - Ex:
    var getElement = window.document.getElementsByTagName['p'](0)
    window.document.write(`Conteúdo dentro de p[0]: ${getElement.innerHTML}`)
- ID:
- Ex:
    < div id="idClickHere"> DIV - CLICK HERE </div>
    var idClickHere = window.document.getElementById('idClickHere')
    idClickHere.style.background = "green"
- Nome:
- Classe:
- Seletor:

## English

- It started as a technology for clients, but now it also works on servers.
- It is an a priori client-side technology.
- A technology that provides many functions.
- NodeJS is primarily involved in porting Java Script to the SERVER side.
- Main technologies derived from JS: JQuery, Angular, React, Electron, Ionic.
