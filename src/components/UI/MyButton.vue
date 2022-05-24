<template>
  <button class="btn" type="submit">
    <slot></slot>
  </button>
</template>

<script>
export default {
}
</script>

<style scoped>
.btn {
  height: 48px;
  width: 204px;
  left: 1004px;
  top: 16px;
  border-radius: 4px;
  background: #6153CC;
  color: white;
  filter: drop-shadow(0px 0px 3px rgba(0, 0, 0, 0.25));
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  line-height: 16px;
  letter-spacing: 1.25px;
  text-transform: uppercase;
}
</style>