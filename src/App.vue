<template>
  <div id="app" style="margin:0px; padding:0px;">
  <!--  <contact></contact>
    <service></service>
    <description></description>
    <exercice></exercice>
    <exercice1></exercice1>
    <footerComponent></footerComponent>-->
    <exercice2></exercice2>

  </div>
</template>

<script>
import contact from './components/contact.vue'
import footerComponent from './components/footer.vue'
import description from './components/description.vue'
import service from './components/service.vue'
import exercice from './components/exerciceconcentrationattention.vue'
import exercice1 from './components/exerciceperceptionvisuelle.vue'

import exercice2 from './components/exercice.vue'


export default {
  name: 'app',
  components: {
    contact,
    footerComponent,
    service,
    description,
    exercice,
    exercice1,
    exercice2
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
