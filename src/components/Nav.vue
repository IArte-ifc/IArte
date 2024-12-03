<template>
  <nav>
    <a href="#landing"><div class="logo"></div><!-- <img src="logo.svg" alt="Logo" class="logo"> --></a>
    <div class="items">
      <a href="#">Sobre o assunto</a>
      |
      <a href="#">IArte</a>
      |
      <a href="#">Imagens</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'appNav',
  props: {
    msg: String
  }
}
</script>

<style scoped>
nav {
  display: flex;
  background-color: rgb(0,0,0);
  color: white;
  width: 100dvw;
  padding: 2rem 8rem;
  /* position: fixed; */
  z-index: 1000;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
