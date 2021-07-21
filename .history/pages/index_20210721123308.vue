<template>
  <div style="margin-top: 250px">
    <center>
      <div class="card card-border" style="">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Special title treatment</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional
              content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </center>
  </div>
</template>
<style scoped>
.card-border::before {
  content: " ";
  width: 105%;
  height: 105%;
  background: linear-gradient(#9198e5, #ffffff);
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
  width: 18rem;
  height: 18rem;
  padding: 1rem;
}
</style>
<script>
export default {};
</script>
