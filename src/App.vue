<template>
  <div id="app">
    <Title/>
    <Hero imgFile="https://i.pinimg.com/564x/e8/4f/a0/e84fa0db16dc951f8d70ef5a0fe74518.jpg"/>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero
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

// reset
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
