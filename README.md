<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AluraBooks</title>
  <link rel="stylesheet" href="reset.css">
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <header class="cabeçalho">
    <div class="container">
      <input type="checkbox" id="menu" class="container__botao" />
      <label for="menu">
        <span class="cabeçalho__menu-hamburguer container__imagem"></span>
      </label>
      <ul class="lista-menu">
        <li class="lista-menu__titulo">Categorias</li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Programação</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Front-end</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Infraestrutura</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Business</a>
        </li>
        <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Design & UX</a>
        </li>
      </ul>
      <img src="img/Logo.svg" alt="Logo da Alurabooks" class="container__imagem">
    </div>
    <div class="container">
      <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
      <a href="#"><img src="img/Compras.svg" alt="Carrinhos de compras" class="container__imagem"></a>
      <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
    </div>
  </header>

  <section class="banner">
    <h2 class="banner__titulo">Já sabe por onde começar?</h2>
    <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!
    <p>
      <input type="search" class="banner__pesquisa" placeholder="Qual será sua próxima leitura?">
  </section>
</body>

</html>
