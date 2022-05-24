<template>
  <div>
    <MyNav></MyNav>
    <MyMenu></MyMenu>
    <MyTableInfo></MyTableInfo>
  </div>
</template>

<script>
import MyNav from '@/components/UI/MyNav'
import MyMenu from '@/components/UI/MyMenu'
import MyTableInfo from "@/components/UI/MyTableInfo";
export default {
  components: {MyTableInfo, MyNav, MyMenu}
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
