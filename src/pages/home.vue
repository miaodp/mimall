<template>
  <div id="home">
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<style>
</style>

<script>
import NavHeader from './../components/NavHeader'
  import NavFooter from './../components/NavFooter'
  export default{
    name:'nav-home',
    components:{
      NavHeader,
      NavFooter
    }
  }
</script>
