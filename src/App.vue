<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  created(){
    console.log("调用APP")
    this.$common.getFlow()
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
}
</style>
