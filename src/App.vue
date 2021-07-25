<template>
  <div id="app">
    <MainComponent/>
  </div>
</template>

<script>
import MainComponent from './components/mainComponent.vue'
export default {
  name: 'App',
  components: {
    MainComponent
  }
  /*async created() {
    var { data }=await axios.get("https://recruitment-mock-data.gjg-ads.io/data") ;
    console.log(data)
  }*/
}
</script>

<style>

</style>
