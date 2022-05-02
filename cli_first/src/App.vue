<template>
  <div id="app">
    
    <FirstTitle/>
    <HeroImg/>

  </div>
</template>

<script>
import FirstTitle from './components/FirstTitle.vue';
import HeroImg from './components/HeroImg.vue';

export default {
  name: 'App',
  components: {
    FirstTitle,
    HeroImg
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
