<template>
  <div id="app">
    <TitoloH1 />
    <BestHero />
  </div>
</template>

<script>
import TitoloH1 from './components/TitoloH1.vue'
import BestHero from './components/BestHero.vue'

export default {
  name: 'App',
  components: {
    TitoloH1,
    BestHero,
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  text-align: center;
  color: white;
  background-color: #2c3e50;
  padding-top: 20px;
}
</style>
