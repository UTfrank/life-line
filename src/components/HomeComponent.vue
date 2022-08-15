<template>
  <header class="container-fluid p-0" id="home">
    <div class="row justify-content-center m-0">
      <NavbarComponent />
      <BannerComponent />
    </div>
  </header>
</template>

<script>
import NavbarComponent from "@/components/NavbarComponent.vue";
import BannerComponent from "@/components/BannerComponent.vue";
export default {
  name: "HomeComponent",
  components: {
    NavbarComponent,
    BannerComponent,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  height: 100vh;
}
</style>
