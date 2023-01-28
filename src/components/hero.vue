<template lang="">
  <div class="hero-container">
    <navBar />
    <div class="hero-content">
      <div class="hero-info">
        <img src="hero-icon.svg" alt="" />
        <h1>Sales Optimization & Data Analysis</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam,
          purus sit amet luctus venenatis, lectus
        </p>
        <button>VIEW DETAILS</button>
      </div>
    </div>
  </div>
</template>
<script>
import navBar from "./navBar.vue";
export default {
  components: {
    navBar,
  },
};
</script>
<style lang="scss">
.hero-container {
  background-image: url("../assets/main-background.png");
  height: 100vh;
  width: 100vw;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  color: white;
  display: flex;
  flex-direction: column;
}
.hero-content {
  height: 100vh;
  display: flex;
  align-items: flex-start;
}
.hero-info {
  margin-top: 5rem;
  margin-left: 13rem;
  width: 30rem;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
}
.hero-info button {
  background: none;
  border-radius: 30.5px;
  border: none;
  background-color: #fba60b;
  padding: 0.8rem 3rem;
  color: white;
  cursor: pointer;
  margin-top: 25px;
}
.hero-content h1 {
  font-size: 52px;
  font-weight: 100;
}
</style>
