<script>
export default {
  name: 'HeaderApp',

  data(){
    return{
      titolo: 'Sono un header'
    }
  }

}
</script>

<template>
  <h2>{{titolo}}</h2>

</template>


<style scoped>
h2 {
  color: red;
}

</style>