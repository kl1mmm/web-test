<template>
  <div>
    <MyNav></MyNav>
    <MyMenu></MyMenu>
  </div>
</template>

<script>
import MyNav from '@/components/UI/MyNav'
import MyMenu from '@/components/UI/MyMenu'
export default {
  components: {MyNav, MyMenu}
}
</script>

<style>
#app {
  font-family: Roboto, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
