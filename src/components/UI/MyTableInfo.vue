<template>
  <div class="container">
    <div class="name"><img src="@/components/UI/Pictures/Calculate.svg" style="width: 36px; height: 36px;"><strong style="font-size: 24px"> Бюджетирование</strong></div>
    <div class="information">
      <MyDroplist>Orgcity planning</MyDroplist>
      <MyButton style="margin-left: 8px">+ Добавить проект</MyButton>
    </div>
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
  justify-content: space-between;
  margin-top: 30px;
  margin-left: 76px;
}
.name {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 248px;
}

.information {
  display: flex;
  flex-direction: row;
}
</style>