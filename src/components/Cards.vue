<template>
  <div class="self">
    <h1>CardSection Works!</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'appCards',
  props: {
    msg: String
  }
}
</script>

<style scoped>
/* .self {
  position: fixed;
} */
</style>
