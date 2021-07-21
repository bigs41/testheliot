<template>
  <div>
    <div class="card" style="width: 18rem">
      <div class="card-body">111</div>
      <div class="card-body">222</div>
    </div>
  </div>
</template>
<style scoped>
.card {
  background-color: #ffffff;
  position: relative;
  z-index: 9;
}
.card::before {
  content: " ";
  width: 18rem;
  height: 600px;
  background-color: #007bff;
  position: absolute;
  z-index: 1;
}
</style>
<script>
export default {};
</script>
