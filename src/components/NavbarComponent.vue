<!-- eslint-disable prettier/prettier -->
<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#">LifeLine</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#comingSoon">Coming Soon</a>
          </li>
        </ul>
        <div class="ms-auto d-flex justify-content-center" role="search">
          <ButtonComponent />
        </div>
      </div>
    </div>
  </nav>
</template>
<!-- eslint-disable prettier/prettier -->
<script>
import ButtonComponent from "@/components/ButtonComponent.vue";
export default {
  name: "NavbarComponent",
  components: {
    ButtonComponent,
  },
};
</script>
<!-- eslint-disable prettier/prettier -->
<style scoped>
nav {
  background-color: #fff;
  position: fixed;
  padding: 1.7rem 0;
}
.navbar-brand {
  font-style: normal;
  font-weight: 800;
  font-size: 1.8rem;
  line-height: 2.1rem;
  text-align: center;
  color: #585ce5;
}

.nav-link,
.nav-link:hover,
.nav-link.active {
  font-style: normal;
  font-weight: 500;
  font-size: 1.6rem;
  line-height: 2.1rem;
  text-align: center;
  color: #585ce5;
}
</style>
