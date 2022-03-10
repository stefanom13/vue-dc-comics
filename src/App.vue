<template>
  <div id="app">

    <MyHeader />
    <!-- header -->

    <MyMain />
    <!-- main -->

    <MyCategories />
    <!-- categories -->

    <MyFooter />
    <!-- footer  -->

  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'
import MyCategories from './components/MyCategories.vue'

export default {
  name: 'App',
  components: {
   MyHeader,
   MyMain,
   MyFooter,
    MyCategories,
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
  font-family: 'League Gothic', sans-serif;
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
.widget{
  @include widget;
}

</style>
