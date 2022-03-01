<template>
  <div class="work text-opening" id="OurWork">
    <div class="col-7 text-right">
      <h2 class="font-35 mb-4 fw-bold">OUR WORK</h2>
      <h3 class="font-30">
        We have established partnerships with many clients in various business
        sectors. We are committed to providing our clients with a sustainable
        and inclusive future to play a crucial role in and beyond the country.
      </h3>
    </div>
    <div class="d-flex flex-row justify-content-between align-items-start">
      <div class="text-2 w-50 me-5">
        <h2 class="font-30 mb-3 fw-bold">Blockchain Technology</h2>
        <hr class="me-5" />

        <div class="d-flex flex-row justify-content-between">
          <div class="me-5">
            <p class="font-25">Kriptosh</p>
            <p class="font-25">Kriptoklub</p>
            <p class="font-25">Moments</p>
          </div>

          <div class="me-5 flex-grow-1 ms-5">
            <p class="font-25">Digital Asset Exchange</p>
            <p class="font-25">Cyptocurrency Community</p>
            <p class="font-25">NFT Marketplace</p>
          </div>
        </div>
      </div>
      <div class="text-2 w-50 ms-5">
        <h2 class="font-30 fw-bold">Food & Beverages</h2>
        <hr class="me-5" />

        <div class="d-flex flex-row justify-content-between">
          <p class="font-25 me-5">Vrew Coffee</p>
          <p class="font-25 flex-grow-1 me-5 ms-5">Premium Coffee Shop</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Work",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.work {
  background: #ffffff;
  height: 100vh;
}

.text-opening {
  padding: 7rem 12rem;
}

.text-2 {
  margin-top: 8rem;
}
</style>
