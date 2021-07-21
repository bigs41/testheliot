<template>
  <div style="margin-top: 250px">
    <center>
      <div class="card" style="width: 18rem; height: 18rem">
        <div class="card-body">111</div>
        <div class="card-body">222</div>
      </div>
    </center>
  </div>
</template>
<style scoped>
.card::before {
  content: " ";
  width: 105%;
  height: 105%;
  background-color: #007bff;
  position: absolute;
  z-index: -1;
  top: -0.5rem;
  left: -0.5rem;
  border-radius: 5px;
  transform: rotate(-4deg);
  -ms-transform: rotate(-4deg);
}
.card {
  background-color: #ffffff;
  position: relative;
}
</style>
<script>
export default {};
</script>
