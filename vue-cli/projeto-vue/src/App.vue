<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <CalculadoraINI name="Calculadora"/>

  </div>
</template>

<script>
import CalculadoraINI from './components/painel/calculadora-ini'

export default {
  name: 'app',
  components: {
    CalculadoraINI
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
