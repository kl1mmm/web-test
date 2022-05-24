<template>
  <header class="header">
    <div class="h-left">
      <img src="@/components/UI/Pictures/Logo.svg">
      <a href="#" class="link">
        <img src="@/components/UI/Pictures/Services.svg"> Сервисы
      </a>
      <a href="#" class="link">
        <img src="@/components/UI/Pictures/Search.svg"> Поиск
      </a>
    </div>
    <div class="h-rigth">
      <a href="#" class="link"><img src="@/components/UI/Pictures/HelpDesk.svg" width="40px" height="40px"></a>
      <a href="#" class="link"><img src="@/components/UI/Pictures/Notifications.svg" width="19px" height="20px"></a>
      <a href="#" class="link"><img src="@/components/UI/Pictures/Ava.svg" width="40px" height="40px"></a>
    </div>
  </header>
</template>

<script>

</script>

<style scoped>
.h-left a{
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.25px;
  color: #2A2D43;
  text-decoration: none;

  margin-left: 46px;
}

.h-left img {
  margin-right: 12px;
}

.h-rigth img {
  margin-left: 30px;
}

.header{
  display: flex;
  justify-content: space-between;
  height: 60px;
}
.h-left {
  display: flex;
  padding: 5px;
}

.h-rigth {
  margin-right: 20px;
  display: flex;
  justify-content: space-evenly;
}

.link {
  display: flex;
  align-items: center;
}
</style>