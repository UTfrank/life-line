<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
     <router-link to="/about">About</router-link> -->
  <!-- </nav> -->
  <!-- <router-view /> -->
  <HomeView />
</template>

<script>
import { onMounted } from "vue";
import AOS from "aos";
import HomeView from "@/views/HomeView.vue";
onMounted(() => {
  AOS.init();
});
export default {
  // name: "HomeComponent",
  components: {
    HomeView,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700;800&display=swap");
html {
  font-size: 62.5%;
}
#app {
  font-family: "Raleway", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
@media (max-width: 75em) {
  html {
    font-size: 50%;
  }
}

@media (max-width: 56.25em) {
  html {
    font-size: 45%;
  }
}
@media (max-width: 37.5em) {
  html {
    font-size: 35%;
  }
}
@media (min-width: 112.5em) {
  html {
    font-size: 75%;
  }
}
</style>
