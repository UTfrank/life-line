<!-- eslint-disable prettier/prettier -->
<template>
  <div class="col-12 timer">
    <div class="row justify-content-center align-items-center">
      <h2 class="timer-heading col-12">
        <div>00 :<br /><span>Days</span></div>
        <div>00 :<br /><span>Hours</span></div>
        <div>00 :<br /><span>Mins</span></div>
        <div>00 <br /><span>Secs</span></div>
      </h2>
    </div>
  </div>
</template>
<!-- eslint-disable prettier/prettier -->
<script>
export default {
  name: "TimerComponent",
};
</script>
<!-- eslint-disable prettier/prettier -->
<style>
.timer-heading {
  display: flex;
}
.timer-heading div {
  font-style: normal;
  font-weight: 700;
  font-size: 7rem;
  text-align: center;
  color: #ffffff;
}
.timer-heading div:not(:last-child) {
  margin-right: 1rem;
}
.timer-heading div span {
  display: block;
  font-style: normal;
  font-size: 2rem;
  text-align: left;
  margin-left: 2rem;
}
</style>
