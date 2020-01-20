<template>
  <div class="hello">
    <h1>{{ name }}</h1>
    <Display />
    <Botoes />
  </div>
</template>

<script>
import  Display  from './display';
import  Botoes  from './botoes';

export default {
  name: 'CalculadoraINI',
  props: {
    name: String
  },
  components:{
    Display, Botoes
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
