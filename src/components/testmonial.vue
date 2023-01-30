<template lang="">
  <div class="testmonials-container">
    <div class="testmonials">
      <div class="testmonials-card">
        <div class="test-text">
          <h1>FREE SEO ANALYSIS</h1>
        </div>
        <input type="text" placeholder="Your Name" style="margin-top: 1rem" />
        <input type="text" placeholder="Email" />
        <input type="text" placeholder="Your Website URL" />
        <input type="text" placeholder="Company Name" />
        <v-btn
          rounded
          color="#FBA60B"
          dark
          style="width: 300px; height: 39px; margin-top: 30px; color: white"
        >
          GET YOUR REPORT
        </v-btn>
        <p>*We will get back to you within 24 hours</p>
      </div>
      <div class="testmonials-description">
        <img src="circle.svg" alt="" />
        <p style="font-size: 20px; color: white; padding-top: 1rem">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam,
          purus sit amet luctus venenatis, lectus magna fringilla urna,
          porttitor rhoncus dolor purus non enim
        </p>
        <p style="font-size: 20px; color: white; padding-top: 1rem">
          Cailee Spaeny
        </p>
        <img src="arrows.svg" alt="" style="margin-top: 1rem" />
      </div>
      <img
        src="testmonials.svg"
        alt=""
        style="height: 600px; width: 100vw; z-index: -1"
      />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.testmonials-container {
  margin-top: 200px;
}

.testmonials-card {
  width: 350px;
  height: 500px;
  border-radius: 30px;
  background-color: white;
  position: absolute;
  margin-left: 300px;
  bottom: 170px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.testmonials-card input {
  background: #ffffff;
  color: black;
  box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.2);
  border-radius: 19.5px;
  width: 300px;
  height: 39px;
  padding: 1rem;
  margin-top: 2rem;
}
.testmonials-card p {
  color: black;
  font-size: 12px;
  margin-top: 1rem;
}
.test-text {
  background-color: #fba60b;
  color: white;
  border-radius: 30px 30px 0 0;
  width: 101%;
  text-align: center;
  padding: 1.35rem 0 1.35rem 0;
}
.test-text h1 {
  font-weight: 400;
}
.testmonials-description {
  position: absolute;
  width: 431px;
  height: 390px;

  left: 873px;
  bottom: 106px;
}
</style>
