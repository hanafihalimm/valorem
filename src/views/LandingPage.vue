<template>
  <div>
    <!-- <Header /> -->
    <Home />
    <Work />
    <Value />
    <Location />
  </div>
</template>

<script>
// import Header from "../components/Header.vue";
import Home from "../components/Home.vue";
import Work from "../components/Work.vue";
import Value from "../components/Value.vue";
import Location from "../components/Location.vue";
export default {
  name: "Landingpage",

  components: {
    // Header,
    Home,
    Work,
    Value,
    Location,
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style scoped></style>
