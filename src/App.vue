<template>
  <ImageSection msg="Just a little bit!"/>
  <CardSection msg="A lot, by the way!"/>
</template>

<script>
import ImageSection from './components/Images.vue';
import CardSection from './components/Cards.vue'

export default {
  name: 'App',
  components: {
    ImageSection,
    CardSection
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
