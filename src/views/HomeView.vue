<template>
  <div class="home">
    <HomeComponent />
    <ComingSoon />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeComponent from "@/components/HomeComponent.vue";
import ComingSoon from "@/components/ComingSoon.vue";

export default {
  name: "HomeView",
  components: {
    HomeComponent,
    ComingSoon,
  },
};
</script>
