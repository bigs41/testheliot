<template>
  <div style="margin-top: 250px">
    <center>
      <div class="card card-border" style="">
        <div class="card text-center">
          <div class="card-body">
            <div class="form-group text-left">
              <label for="yourName">Your Name</label>
              <input
                type="text"
                class="form-control"
                id="yourName"
                placeholder="Your Name"
                v-model="name"
              />
            </div>
            <a href="#" class="btn btn-primary">Calculate</a>
          </div>
        </div>
        <h5 class="card-title">Your age is {{ age }}</h5>
      </div>
    </center>
  </div>
</template>
<style scoped>
.card-title {
  margin-top: 10px;
}
.card-border::before {
  content: " ";
  width: 105%;
  height: 105%;
  background: linear-gradient(251deg, #9198e5, #c9ccf3);
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
import axios from "axios";
export default {
  data() {
    return {
      name: "",
      age: 0,
    };
  },
  methods: {
    async getdata() {
      let params = new url.URLSearchParams({ name: this.name });
      const res = await axios.get(`https://api.agify.io?${params}`);
      console.log(res);
    },
  },
};
</script>
