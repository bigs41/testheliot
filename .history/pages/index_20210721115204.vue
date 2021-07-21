<template>
  <div style="margin-top: 250px">
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
  top: -0.35rem;
  border-radius: 5px;
  -ms-transform: rotate(-3deg);
  transform: rotate(-3deg);
}
.card {
  background-color: #ffffff;
  position: relative;
}
</style>
<script>
export default {};
</script>
