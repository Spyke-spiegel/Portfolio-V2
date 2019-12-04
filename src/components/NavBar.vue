<template>
  <div class="container">
    <div class="navbar">
      <div class="logo">
        <h1>Florent Ayot</h1>
      </div>
      <div class="menu">
        <h3>About</h3>
        <h3>Portfolio</h3>
        <h3>Github</h3>
        <h3>Contact</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style scoped>
.navbar {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-color: #343434;
  color: gold;
  align-items: center;
  height: 10vh;
}

.menu {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

h1 {
  margin: 0 25px 0 25px;
  font-family: "Dancing Script", cursive;
  font-weight: bold;
  font-size: 50px;
}

h3 {
  font-family: "Montserrat";
  font-size: 35px;
}

.menu > h3 {
  margin: 0 25px 0 25px;
}
</style>