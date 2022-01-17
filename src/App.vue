<template>
  <Navigation/>
</template>

<script>
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Navigation
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  .fade-enter-active,
  .fade-leave-active {
      transition:  0.4s  transform;
  }
  .fade-enter-from,
  .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
      transform: translateX(-250px);
  }
  .fade-enter-to{
      transform: translateX(0);
  }

  .scale-enter-active,
  .scale-leave-active {
      transition:  0.2s ease all;
  }
  .scale-enter-from,
  .scale-leave-to /* .scale-leave-active below version 2.1.8 */ {
      transform: scale(85%);
      opacity: 0.4;
  }
  .scale-enter-to{
      transform: scale(100%);
      opacity: 1;
  }

}
</style>
