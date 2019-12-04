<template>
  <div class="container">
    <div class="bg-img"></div>
    <div class="bg-logo">
      <img src="../assets/florent_profile-min.jpg" />
      <h1>Florent Ayot</h1>
      <h3>Programmer Full-Stack</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped>
.bg-img {
  background-image: url("../assets/coding.jpeg");
  filter: blur(15px);
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.bg-logo {
  font-weight: bold;
  color: gold;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  padding: 20px;
  text-align: center;
}

.bg-logo > img {
  height: 250px;
  weight: 250px;
  border-radius: 50%;
}
</style>