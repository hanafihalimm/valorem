<template>
  <div class="app" id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
.app {
  font-family: "Noto Sans", sans-serif;
  scroll-behavior: smooth;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.font-35 {
  font-size: 35px;
}

.font-30 {
  font-size: 30px;
}

.font-25 {
  font-size: 25px;
}

.font-24 {
  font-size: 24px;
}
</style>
