<template>
  <div class="container">
    <MyDroplist class="elem ">📅 По месяцам</MyDroplist>
    <MyDroplist class="elem">🗄 Настройка табл.</MyDroplist>
    <MyButton class="btn">⇧Выгрузка</MyButton>
    <a HREF="#"><img src='@/components/UI/Pictures/Voronka.svg' style="width: 18px; height: 12px; margin-left: 23px;"></a>
    <a HREF="#"><img src='@/components/UI/Pictures/Download.svg' style="width: 14px; height: 17px; margin-left: 23px;"></a>
  </div>
</template>

<script>
import MyDroplist from "@/components/UI/MyDroplist";
import MyButton from "@/components/UI/MyButton";
export default {
  components: {MyButton, MyDroplist}
}
</script>

<style scoped>
.container {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  margin-top: 25px;
}

.elem {
  width: 180px;
  height: 30px;
  margin-right: 15px;
}

.btn {
  width: 120px;
  height: 30px;
  background: white;
  color: black;
}
</style>