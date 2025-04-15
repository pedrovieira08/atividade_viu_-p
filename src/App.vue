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
        </ul>
      </nav>
    </header>
    <main>
      <section class="book">
        <div>
          <p class="autor">Autor de Abril</p>
          <h2>Eric-Emanuel Schmitt </h2>
          <p>Eric-Emmanuel Schmitt has been awarded more than 20 literary prizes and distinctions, and in 2001 he received the title of Chevalier des Arts et des Lettres. His books have been translated into over 40 languages.</p>
          <button>Acessar página do livro</button>
        </div>
        
      </section>
    </main>
  </body>

</template>
<style scoped>
a{
    color: black;
    text-decoration: none;
}
/*==================================
               topo
====================================*/
header{
  display: flex;
  justify-content:space-between;
  align-items: center;
  margin: 15px 0px 15px 0px;
  
}header div h1{
  font-size: 2rem;
}
header nav ul{
  display: flex;
  align-items: center; 
  list-style: none;
}header div{
  display: flex;
}header div p{
  color: #27AE60;
  text-align: center;
  font-size: larger;
}
header nav ul li a{
  padding: 20px;
  justify-content: space-between;

}
/* book */
section.book{
 padding: 180px;
  border-top: solid 2px;
  border-bottom: solid 2px;
  
}section.book div p.autor{
  border: solid 2px;
  border-radius: 60px;
  margin: 10px;
  padding: 10px;
}
</style>
