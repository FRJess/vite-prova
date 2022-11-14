<script>

import HeaderApp from './components/HeaderApp.vue';

export default {
  name: 'App',
  components: {
    HeaderApp
  },

  data(){
    return{
      titolo: 'Ciao Vue Vite'
    }
  }
}

</script>

<template>

  <HeaderApp/>
  <div class="container">
    <h1>{{titolo}}</h1>
  </div>


</template>

<style>

</style>