<script setup>
</script>
<template>

  <body>
    <header>
      <div>
        <h1>IFbooks</h1>
        <p>
          Apreço a <br>
          leitura
        </p>
      </div>
      <nav>
        <ul>
          <li>
            <a href="#">Termos</a>
          </li>
          <li>
            <a href="#">Equpe</a>
          </li>
          <li>
            <a href="#">Envio</a>
          </li>
          <li>
            <a href="#">Devoluções</a>
          </li>
          <li class="icons">
            <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">!Font Awesome Free 6.7.2 by
                @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2025
                Fonticons, Inc.
                <path
                  d="M0 24C0 10.7 10.7 0 24 0L69.5 0c22 0 41.5 12.8 50.6 32l411 0c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3l-288.5 0 5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5L488 336c13.3 0 24 10.7 24 24s-10.7 24-24 24l-288.3 0c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5L24 48C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z" />
              </svg></a>
          </li>
          <li class="icons">
            <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">!Font Awesome Free 6.7.2 by
                @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2025
                Fonticons, Inc.
                <path
                  d="M47.6 300.4L228.3 469.1c7.5 7 17.4 10.9 27.7 10.9s20.2-3.9 27.7-10.9L464.4 300.4c30.4-28.3 47.6-68 47.6-109.5v-5.8c0-69.9-50.5-129.5-119.4-141C347 36.5 300.6 51.4 268 84L256 96 244 84c-32.6-32.6-79-47.5-124.6-39.9C50.5 55.6 0 115.2 0 185.1v5.8c0 41.5 17.2 81.2 47.6 109.5z" />
              </svg></a>
          </li>
          <li class="icons">
            <a href="#"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">!Font Awesome Free 6.7.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2025 Fonticons, Inc.<path d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512l388.6 0c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304l-91.4 0z"/></svg></a>
          </li>
        </ul>

      </nav>
    </header>
    <main>
      <section class="book">
        <div>
          <p class="autor">Autor de Abril</p>
          <h2>Eric-Emanuel Schmitt </h2>
          <p>Eric-Emmanuel Schmitt has been awarded more than 20 literary prizes and distinctions, and in 2001 he
            received the title of Chevalier des Arts et des Lettres. His books have been translated into over 40
            languages.</p>
          <button>Acessar página do livro</button>
        </div>

      </section>
    </main>
  </body>

</template>
<style scoped>
a {
  color: black;
  text-decoration: none;
}

/*==================================
               topo
====================================*/
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 15px 0px 15px 0px;

}

header div h1 {
  font-size: 2rem;
  border-right: solid #27AE60;
  margin: 0px 10px 0px 0px;
  padding: 0px 10px 0px 0px;
}

header nav ul {
  display: flex;
  align-items: center;
  list-style: none;
}

header div {
  display: flex;
}

header div p {
  color: #27AE60;
  text-align: center;
  font-size: larger;
}

header nav ul li a {
  padding: 20px;
  justify-content: space-between;
}
header nav ul li.icons a svg{
  border-right: solid #27AE60;
  width: 20%;
  margin: 0px 10px 0px 0px;
  padding: 0px 10px 0px 0px;
}

/* book */

section.book {
  padding: 180px;
  border-top: solid 2px;
  border-bottom: solid 2px;
  border-color: #27AE60;

}

section.book div p.autor {
  border: solid 2px;
  border-radius: 60px;
  margin: 10px;
  padding: 10px;
  border-color: #27AE60;
}
</style>
