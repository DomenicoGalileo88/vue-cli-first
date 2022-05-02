<template>
  <div id="app">
    
    <FirstTitle/>
    <HeroImg/>
    <SecondComponents/>

  </div>
</template>

<script>
import FirstTitle from './components/FirstTitle.vue';
import HeroImg from './components/HeroImg.vue';
import SecondComponents from './components/SecondComponents.vue';

export default {
  name: 'App',
  components: {
    FirstTitle,
    HeroImg,
    SecondComponents
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
