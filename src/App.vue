<template>
  <appNav msg="This Should be a Nav..."/>
  <appImages msg="Just a little bit!"/>
  <appCards msg="A lot, by the way!"/>
  <appFooter msg="And this should be a footer..."/>
</template>

<script>
import appNav from './components/Nav.vue'
import appImages from './components/Images.vue';
import appCards from './components/Cards.vue';
import appFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    appNav,
    appImages,
    appCards,
    appFooter
  }
}
</script>

<style>
* {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
