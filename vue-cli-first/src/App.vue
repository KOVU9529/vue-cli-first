<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <!--Utilizzo il componente-->
    <MyTitle titolo="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>

//importo il componente
import MyTitle from './components/MyTitle.vue'


export default {
  name: 'App',
  
  //Definisco il componente
  components: {
    MyTitle
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
