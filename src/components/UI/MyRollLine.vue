<template>
  <footer class="footer">
    <div class="left-footer">
      <div class="footer-text">Выводить строк на страницу:</div>
      <div class="count">
        <MyDroplist class="page-count">50</MyDroplist>
      </div>
    </div>
    <div class="rigth-footer">
      <div class="footer-text" style="margin-right: 24px">1-50 из 560</div>
      <a href="#" style="margin-right: 24px">
      <svg width="8" height="13" viewBox="0 0 8 13" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M7.415 11.335L2.83 6.75L7.415 2.165L6 0.75L0 6.75L6 12.75L7.415 11.335Z" fill="#BFC0C7"/>
      </svg>
      </a>
      <a href="#">
      <svg width="8" height="13" viewBox="0 0 8 13" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M0.584961 11.46L5.16996 6.875L0.584961 2.29L1.99996 0.875L7.99996 6.875L1.99996 12.875L0.584961 11.46Z" fill="#2A2D43"/>
      </svg>
      </a>
    </div>
  </footer>
</template>

<script>
import MyDroplist from "@/components/UI/MyDroplist";
export default {
  components: {MyDroplist}
}
</script>

<style scoped>
.footer{
  position: absolute;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 46px;
  margin-left: 55px;
  bottom: 15px;
}

.footer-text{
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
  letter-spacing: 0.4px;
}

.left-footer{
  display: flex;
  align-items: center;
  margin-left: 16px;
}

.page-count{
  display: flex;
  width: 40px;
  height: 30px;
  justify-content: space-evenly;
  align-items: center;
  margin-left: 16px;
  padding: 5px;
  background: #ECEAF9;
}

.rigth-footer {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  width: 1100px;
}
</style>