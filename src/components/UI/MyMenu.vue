<template>
  <div class="container">
    <div class="upside">
      <div class="click">
    <img class="MainPicMenu" src="@/components/UI/Pictures/LogoMenu1.svg" style="width: 34px; height: 34px; margin-top: 30px;">
      </div>
      <div class="click">
    <img class="PicMenu" src="@/components/UI/Pictures/HomeLogo.svg">
      </div>
      <div class="click-active">
    <img class="PicMenu" src="@/components/UI/Pictures/StaffLogo.svg">
      </div>
      <div class="click">
    <img class="PicMenu" src="@/components/UI/Pictures/HoursLogo.svg">
      </div>
      <div class="click">
    <img class="PicMenu" src="@/components/UI/Pictures/CalculateLogo.svg">
      </div>
      <div class="end-section">
        <div class="click">
      <img class="ArrowNext" src="@/components/UI/Pictures/Arrow.svg">
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style scoped>
.container {
  position: absolute;
  left: 0px;
  display: flex;
  flex-direction: column;
  background: #D0CBF0;
  height: 92.6%;
  width: 60px;
}

.PicMenu {
  width: 28px;
  height: 28px;
  margin-top: 45px;
  align-self: center;
}

.ArrowNext {
  width: 14px;
  height: 14px;
  margin-top: 22em;
}

</style>