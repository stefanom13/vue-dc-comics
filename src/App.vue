<template>
  <div id="app">
    <MyHeader />
    
    <!-- header -->
    <MyMain />
    <!-- main -->

    <!-- footer  -->
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'

export default {
  name: 'App',
  components: {
   MyHeader,
   MyMain,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  
}
</style>
