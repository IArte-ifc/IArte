<template>
  <appNav />
  <div class="outer-container">
    <aside> <!-- CARDS -->
      <appCards />
    </aside> 



    <main> <!-- IMAGES -->
      <appImages />
    </main>
    <appTexto />
  </div>


  <appFooter msg="And this should be a footer..."/>
</template>

<script>
import appNav from './components/Nav.vue'
import appImages from './components/Images.vue';
import appCards from './components/Cards.vue';
import appTexto from './components/Texto.vue';
import appFooter from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    appNav,
    appImages,
    appCards,
    appTexto,
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
  background-color: rgb(31, 29, 29);
  width: 30%;
  min-height: 100dvh;
}

main {
  background-color: #FFFFFF;
  width: 70%;
  min-height: 100dvh;
  text-align: center;
}

@media (max-width: 430px) {
  aside {
    width: 0;
  }

  main {
    width: 100%;
  }
}

</style>