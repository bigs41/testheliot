<template>
  <div style="margin-top: 250px">
    <center>
      <div class="card card-border" style="width: 18rem; height: 18rem">
        <div class="card-body">111</div>
        <div class="card-body">222</div>
      </div>
    </center>
  </div>
</template>
<style scoped>
.card-border::before {
  content: " ";
  width: 105%;
  height: 105%;
  background-color: #007bff;
  position: absolute;
  z-index: -1;
  top: -0.5rem;
  left: -0.5rem;
  border-radius: 1.25rem;
  transform: rotate(-7deg);
  -ms-transform: rotate(-7deg);
}
.card-border {
  background-color: #ffffff;
  position: relative;
  border-radius: 1.25rem;
}
</style>
<script>
export default {};
</script>
