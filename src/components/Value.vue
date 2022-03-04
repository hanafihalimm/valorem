<template>
  <div class="bg-value" id="Value">
    <div class="value">
      <h1 class="font-35 fw-bold text-white mb-5">OUR VALUE</h1>
      <h3 class="font-30 text-white">
        These core values define who we are and what we do.
      </h3>
    </div>
    <div class="border border-white">
      <p class="font-30 text-center text-white fw-bold">Congruency</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Value",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped>
.bg-value {
  background: #000000;
  height: 100vh;
}

.value {
  padding: 7rem 12rem;
}

.border {
  margin-left: 0.25rem;
  margin-right: 0.25rem;
  border-radius: 10px;
}
</style>
