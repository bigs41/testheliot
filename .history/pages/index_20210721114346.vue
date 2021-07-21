<template>
  <div>
    <div class="card" style="width: 18rem">
      <div class="card-body">111</div>
      <div class="card-body">222</div>
    </div>
  </div>
</template>
<style scoped>
.card::after {
  content: " ";
  width: 100%;
  height: 100%;
  background-color: #007bff;
  position: absolute;
  z-index: 1;
  top: 0rem;
  -ms-transform: rotate(-5deg);
  transform: rotate(-5deg);
}
.card {
  background-color: #ffffff;
  position: relative;
  z-index: 9;
}
</style>
<script>
export default {};
</script>
