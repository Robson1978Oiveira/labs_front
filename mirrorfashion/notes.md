<a> elemento âncora, com o atributo href interligam as páginas web.
<ul>
  <li><a href="https://example.com">Website</a></li>
</ul>

<article> representa uma composição independente em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sind

<div> é um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica (tal como <article> ou <nav>).
<div>
  <h2>Cabeçalho</h2>
  <img src="passaro.jpg" alt="pássaro" />
</div>


<nav> representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.
<nav>
  <ul>
    <li><a href="#">Página inicial</a></li>
  </ul>
</nav>

<header> representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.

<section> <section> representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.
<section>
  <h2>Cabeçalho</h2>
  <img src="passaro.jpg" alt="pássaro" />
</section>

<input> é usado para criar controles interativos para formulários baseados na web para receber dados do usuário. A semântica de um <input> varia consideravelmente dependendo do valor de seu atributo type.

<label> **representa uma legenda para um item em uma interface de usuário. 
<label>Click me <input type="text" id="User" name="Name" /></label>
<label for="User">Click me</label> <input type="text" id="User" name="Name" />

<optgroup> cria um agrupamento de opções dentro do elemento <select>.
<select>
  <optgroup label="Grupo 1">
    <option>Opção 1.1</option>
  </optgroup>

  <img> **(or HTML Image Element) representa a inserção de imagem no documento, sendo implementado também pelo HTML5 para uma melhor experiência com o elemento <figure> e <figcaption>.
  <figure>
  <img src="imagem.jpg" alt="Minha Figura">
  <figcaption>Informações da Figura</figcaption>
  </figure>



