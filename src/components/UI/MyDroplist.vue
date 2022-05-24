<template>
  <select class="form-select" aria-label="Default select example">
    <option selected><slot></slot></option>
    <option value="1"></option>
    <option value="2"></option>
  </select>
</template>

<script>
export default {
}
</script>

<style scoped>
.form-select {
  font-size: 14px;
  height: 48px;
  width: 200px;
  left: 0px;
  top: 0px;
  border-radius: 4px;
  filter: drop-shadow(0px 0px 3px rgba(0, 0, 0, 0.25));
}
</style>