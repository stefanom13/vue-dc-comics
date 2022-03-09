<template>
  <div id="app">

    <MyHeader />
    <!-- header -->

    <MyMain />
    <!-- main -->

    <MyFooter />
    <!-- footer  -->

  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
   MyHeader,
   MyMain,
   MyFooter,
  }
}
</script>

<style lang="scss" >
@import './assets/scss/_mixins.scss';

// generals rule
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

ul {
  list-style: none;
}
a{
  text-decoration: none;
  color: currentColor;
}

// #app {
  
// }

.container{
  @include container;
}
</style>
