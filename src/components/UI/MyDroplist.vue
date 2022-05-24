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
  width: 23em;
  margin: 0.5em 1em;
  border-radius: 4px;
}
</style>