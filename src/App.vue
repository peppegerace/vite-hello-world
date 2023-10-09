<script>
import AppTitle from './components/AppTitle.vue'
import AppTitleVue from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue';


export default {
  name: 'App',
  components:{
    AppTitle,
    AppHero
  }
}
</script>


<template>
  <AppTitle/>
  <AppHero/>
  <h1>Componente App</h1>
</template>


<style>
body {
  background-color: lightcoral;
  color: darkslateblue;
}
</style>