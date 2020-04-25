# Quarentena_T01
## Trabalho de desenvolvimento web para a quarentena. Relembrando conceitos.
### html 
HTML é a sigla de HyperText Markup Language, expressão inglesa que significa "Linguagem de Marcação de Hipertexto". Consiste em uma linguagem de marcação utilizada para produção de páginas na web, que permite a criação de documentos que podem ser lidos em praticamente qualquer tipo de computador e transmitidos pela internet.
### tags html
Tags são rótulos usados para informar ao navegador como  deve ser apresentado o site. Ou seja, quando começo a escrever HTML  estou escrevendo tags que serão interpretadas pelo navegador, produzindo assim o visual do seu site.
### estrutura de um documento html simples
Um documento HTML começa com a tag HTML e termina com a marca /HTML. Ele também contém um cabeçalho que descreve o título da página e um corpo no qual se encontra o conteúdo da página. O cabeçalho é delimitado pelas tags HEAD e /HEAD. Já o corpo é delimitado pelas tags BODY e /BODY.
### Exemplos de tags html 
01 - Tags de estrutura
<header></header> – Essas tags definem um cabeçalho.
<main></main> – Essas tags representam o conteúdo principal do seu corpo, ou seja, o conteúdo relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação;
<footer></footer> – Essas tags definem um rodapé para a página, geralmente utilizadas no final da página;
<section></section> – Essas tags definem uma sessão para sua página;
<article></article> – Essas tags definem um artigo da sua página.
<aside></aside> – Essas tags representam uma seção de uma página cujo conteúdo é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo;
<nav></nav> – Essa tag define um conteúdo de navegação.
<div></div> – Define uma divisão da página.

02 - Tags de conteúdo

02.01 - De título 

<h1> </h1> - Título de maior valor hierárquico
<h2> </h2>
<h3> </h3>
<h4> </h4>
<h5> </h5>
<h6> </h6> - Título de menor valor hierárquico

02.02 - Tags de texto

<p></p> – Principal tag de texto, compõe um parágrafo;
<span></span> – Apesar de ter uma funcionalidade e características parecidas com os parágrafos, costumam ser utilizadas apenas para pequenas informações, como legendas de um formulário, legendas de uma imagem, etc. Também pode ser utilizada para formar um container;
<pre></pre> – Tag utilizada para representar texto pré-formatado.
<b></b> – Transforma o conteúdo em negrito;
<i></i> – Transforma o conteúdo em itálico;
<br/> – Essa tag não necessita de fechamento, ela executa a função de quebra de linha.
<hr/> – Essa tag não necessita de fechamento, ela forma uma linha horizontal.

### Estililização de tags html
01 - cor 

body {
  color: #333;
}

02 - fonte
p {
    font-size: 16px;
    margin-bottom: 1.5em;
    line-height: 1.4em;
}
