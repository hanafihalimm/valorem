<template>
  <div class="bg-location" id="Contact">
    <div>
      <h2 class="text-location text-35 fw-bold">OUR LOCATION</h2>
    </div>
    <div>
      <span class="border border-dark">
        <div
          id="map-container-google-9"
          class="embended-responsive embeed-responsive map-container-5"
          style="height: 300px"
        >
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.1856337840413!2d106.83029121476922!3d-6.239247595483661!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f3c2f706cbd1%3A0xb71ad8cf236707f0!2sGraha%20Surveyor%20Indonesia%2C%20Jl.%20Gatot%20Subroto%20No.Kav%2056%2C%20RT.1%2FRW.4%2C%20Kuningan%20Tim.%2C%20Kecamatan%20Setiabudi%2C%20Kota%20Jakarta%20Selatan%2C%20Daerah%20Khusus%20Ibukota%20Jakarta%2012950!5e0!3m2!1sid!2sid!4v1646106678715!5m2!1sid!2sid"
            width="600"
            height="450"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
          ></iframe>
        </div>
      </span>
    </div>

    <div class="footer text-end">
      <p class="font-24 fw-bold">THE VALOREM PARTNERS</p>
      <p class="font-24">Contact Us</p>
      <p class="font-24">&copy; The Valorem Partners</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Location",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.bg-location {
  background: #ffffff;
  height: 120vh;
}

.text-location {
  padding: 7rem 30rem;
}

.footer {
  padding-right: 25rem;
}
.map-container-5 {
  overflow: hidden;
  position: relative;
  height: 0;
}
</style>
