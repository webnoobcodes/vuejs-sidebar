<template>
  <div id="app">
    <Sidebar />
  </div>
</template>

<script>
  import Sidebar from './components/Sidebar.vue'

  export default {
    components: {
      Sidebar
    }
  }
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Anton');
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Anton', Arial, Helvetica, sans-serif;
    font-size: 1rem;
    letter-spacing: 1px;
    color: #322F42;
    width: 100%;
    min-height: 100vh;
    background: url('./assets/app_bg.jpg') center center;
    background-size: cover;
    overflow: hidden;
  }
</style>
