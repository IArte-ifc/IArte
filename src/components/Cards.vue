<template>
  <div class="self">
    <div class="container">
      <div class="card">
        <h3>Sobre o projeto</h3>
        <p>&gt;</p>
      </div>
      <div class="card">
        <h3>Mais sobre a ideia</h3>
        <p>&gt;</p>
      </div>
      <div class="card">
        <h3>Objetivos do projeto</h3>
        <p>&gt;</p>
      </div>
      <div class="card">
        <h3>A experiência</h3>
        <p>&gt;</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'appCards',
}
</script>

<style scoped>
.self {
  display: block;
  padding: 7rem 2rem;
}

.container {
  position: fixed;
}

.card {
  background-color: blue;
  padding: 1rem;
  width: 20dvw;
  display: flex;
  margin-bottom: 1rem;
  border-radius: 0px 25px 25px 0px;
  -webkit-border-radius: 0px 25px 25px 0px;
  -moz-border-radius: 0px 25px 25px 0px;
}

@media (max-width: 390px) {
  .self {
    display: none;
  }
}
</style>
