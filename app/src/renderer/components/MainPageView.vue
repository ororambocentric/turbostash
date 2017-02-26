<template>
  <div>
    <img src="./MainPageView/assets/logo.png" alt="electron-vue">
    <h1>Welcome.</h1>
    <current-page></current-page>
    <versions></versions>
    <links></links>
  </div>
</template>

<script>
  import CurrentPage from './MainPageView/CurrentPage'
  import Links from './MainPageView/Links'
  import Versions from './MainPageView/Versions'
  export default {
    components: {
      CurrentPage,
      Links,
      Versions
    },
    name: 'main-page'
  }
</script>

<style scoped>
  img {
    width: 90px;
  }
</style>
