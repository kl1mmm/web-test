<template>
  <div class="screen">
    <MyNav></MyNav>
    <MyMenu></MyMenu>
    <MyTableInfo></MyTableInfo>
    <MyTableSort></MyTableSort>
    <div class="footer">
    <MyRollLine></MyRollLine>
    </div>
  </div>
</template>

<script>
import MyNav from '@/components/UI/MyNav'
import MyMenu from '@/components/UI/MyMenu'
import MyTableInfo from "@/components/UI/MyTableInfo";
import MyTableSort from "@/components/UI/MyTableSort";
import MyRollLine from '@/components/UI/MyRollLine';
export default {
  components: {MyTableSort, MyTableInfo, MyNav, MyMenu, MyRollLine}
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
