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
}
</script>

<style scoped>
nav {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgb(0,0,0);
  color: white;
  width: 100dvw;
  padding: 2rem 0;
  position: fixed;
  z-index: 1000;

  a {
    color: #58E576;
  }

  a:hover {
    color: #66BB79
  }
}

</style>
