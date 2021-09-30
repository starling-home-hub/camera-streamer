<template>
  <div id="app">
    <Streamer />
  </div>
</template>

<script>
  import Streamer from './components/Streamer.vue';

  export default {
    name: 'App',
    components: {
      Streamer
    }
  };
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>
