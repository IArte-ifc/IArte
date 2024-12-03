<template>
  <appNav />
  <div class="outer-container">
    <aside> <!-- CARDS -->
      <appCards msg="A lot, by the way!"/>
    </aside> 



    <main> <!-- IMAGES -->
      <appImages msg="Just a little bit!"/>
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
  text-align: center;
  color: #2c3e50;
}

.outer-container {
  display: flex;
}

aside, main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
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
}
</style>
