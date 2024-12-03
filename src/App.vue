<template>
  <appNav />
  <div class="outer-container">
    <aside> <!-- CARDS -->
      <appCards />
    </aside> 



    <main> <!-- IMAGES -->
      <appImages />
    </main>
  </div>


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
  color: #2c3e50;
}

.outer-container {
  display: flex;
}

aside, main {
  display: flex;
  color: white
}

aside {
  background-color: #3a3de3;
  width: 30%;
  min-height: 100dvh;
}

main {
  background-color: #e33a3a;
  width: 70%;
  min-height: 100dvh;
  text-align: center;
}
</style>
