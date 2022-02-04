<template>
  <div class="" id="Home">
    <div class="image-home">
      <div class="">
        <div class="col-8 group-text position-absolute ms-5 px-5 py-4">
          <h1 class="title-font text-right text-white mb-5 fw-bold">
            The Valorem Partners
          </h1>
          <h3 class="text-white">
            We value our partner’s business initiatives and help them establish
            business connections, growth, and long-term success by overcoming
            their greatest challenges.
          </h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ValoremHome",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.image-home {
  background-image: url("../assets/background.png");
  background-position: center;
  background-size: cover;
  /* width: 100vw; */
  height: 100vh;
}
.title-font {
  font-size: 35px;
}
.group-text {
  bottom: 100px;
}
</style>
