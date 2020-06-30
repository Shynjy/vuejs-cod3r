<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator />
  </div>
</template>

<script>
  import Calculator from './main/Calculator'

  export default {
    components: { Calculator }
  };
</script>

<style>
    @font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Thin.ttf");
    }

    * {
    font-family: "RobotoMono", monospace;
    }

    body {
    margin: 0;
    }

    #app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #ffffff;
    background: #292e49; /* fallback for old browsers */
    background: -webkit-linear-gradient(
        to right,
        #536976,
        #292e49
    ); /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(
        to right,
        #536976,
        #292e49
    ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    -webkit-font-smoothing: antialiased;
    }
</style>