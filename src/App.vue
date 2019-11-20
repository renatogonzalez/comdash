<template lang='pug'>
  #app
    UsersBox
    InfoBox
    PicksBox
    AboutBox
    Prueba
</template>

<script>
import UsersBox from './components/UsersBox.vue'
import InfoBox from './components/InfoBox.vue'
import PicksBox from './components/PicksBox.vue'
import AboutBox from './components/AboutBox.vue'
import Prueba from './components/Prueba.vue'

export default {
  name: 'app',
  components: {
    UsersBox,
    InfoBox,
    PicksBox,
    AboutBox,
    Prueba
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
