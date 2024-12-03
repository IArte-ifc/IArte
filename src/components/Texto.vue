<template>
  <div class="self">
    <h1>{{ h1 }}</h1>
    <p>{{ p }}</p>
  </div>

</template>

<script>
export default {
  name: 'appTexto',
  props: {
    h1: String,
    p: String
  }

}
</script>

<style scoped>
.self {
  padding: 7rem 0;
}

@media (max-width: 390px) {
  .self img {
    width: 80%;
    margin-bottom: 2rem;
  }
}
</style>
