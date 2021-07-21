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
  height: 100%;
  background-color: #007bff;
  position: absolute;
  z-index: 9999;
  top: 0rem;
  -ms-transform: rotate(-5deg);
  transform: rotate(-5deg);
}
</style>
<script>
export default {};
</script>
