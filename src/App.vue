<template>
  <div class="container-flex">
    <div class="row">
      <div class="col-12">
        <base-header></base-header>
      </div>
    </div>
    <base-sidebar></base-sidebar>
  </div>
</template>

<script>
import BaseHeader from "./components/layout/header/BaseHeader.vue";
import BaseSidebar from "./components/layout/sidebar/BaseSidebar.vue";

export default {
  name: "App",
  components: {
    BaseHeader,
    BaseSidebar,
  },
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
}
#app {
  height: 100%;
  width: 100vw;
}
* {
  box-sizing: border-box;
}
</style>
