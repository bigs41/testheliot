<template>
  <div>
    <center>
      <div class="card" style="width: 18rem">
        <div class="card-body">111</div>
        <div class="card-body">222</div>
      </div>
    </center>
  </div>
</template>
<style scoped>
.card::before {
  content: " ";
  width: 101%;
  height: 101%;
  background-color: #007bff;
  position: absolute;
  z-index: -1;
  top: -1rem;
  -ms-transform: rotate(-5deg);
  transform: rotate(-5deg);
}
.card {
  background-color: #ffffff;
  position: relative;
}
</style>
<script>
export default {};
</script>
