<template>
 <header>
   <span class="texto-header"> Home </span>
   <span class="separador">| </span>
   <span class="texto-header">Jogadores</span>
    <span class="separadpr"> | </span>
   <span class="texto-header"> Times</span>
   </header>
 <main> Main</main>
 <footer> Rodapé </footer>

</template>

<style>
@import "./assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem;*/
  height: 100vh;

  font-weight: normal;
}

header, footer{
  background-color: gray;
  height: 15%;
  font-size: 1.3rem;
  color: aliceblue;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
}

main{
  min-height: 70%;
}

header span{
  padding:0 10px;
}
</style>
