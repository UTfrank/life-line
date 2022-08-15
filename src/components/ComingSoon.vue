<!-- eslint-disable prettier/prettier -->
<template>
  <section class="coming-soon container-fluid" id="comingSoon">
    <div class="container">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-md-6 col-12 mb-5 mb-md-0">
          <h2 class="coming-soon-heading col-12">
            <span>coming soon</span>
            lifeline
          </h2>
          <TimerComponent />
        </div>
        <div class="col-md-6 col-12 coming-soon-img mt-5 mt-md-0">
          <img src="@/assets/life-line-phone.svg" class="img-fluid" />
        </div>
      </div>
    </div>
  </section>
</template>
<!-- eslint-disable prettier/prettier -->
<script>
import TimerComponent from "@/components/TimerComponent";
export default {
  name: "ComingSoon",
  components: { TimerComponent },
};
</script>
<!-- eslint-disable prettier/prettier -->
<style>
.coming-soon {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #585ce5;
}
@media (max-width: 37.5em) {
  .coming-soon {
    padding: 5rem 3rem;
  }
}
.coming-soon-heading {
  font-family: "Poppins", sans-serif;
  font-style: normal;
  font-weight: 800;
  font-size: 9.6rem;
  line-height: 3.6rem;
  color: #ffffff;
  text-transform: uppercase;
  margin-left: 0;
  margin-bottom: 6rem;
}
.coming-soon-heading span {
  display: block;
  font-family: "Raleway", sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 2.4rem;
  line-height: 2.8rem;
  color: #ffffff;
  margin-bottom: 3rem;
}
.coming-soon-img {
  height: 70vh;
  display: flex;
  justify-content: center;
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
  background-image: url(@/assets/spiral.svg);
}
</style>
