<template>
  <v-app>
    <v-main>
      <hero />
      <mainBody />
      <testmonial />
      <news />
      <footerr />
    </v-main>
  </v-app>
</template>

<script>
import hero from "./components/hero.vue";
import mainBody from "./components/mainBody.vue";
import testmonial from "./components/testmonial.vue";
import news from "./components/news.vue";
import footerr from "./components/footerr.vue";

export default {
  name: "App",
  components: {
    hero,
    mainBody,
    testmonial,
    news,
    footerr,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;600&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
</style>
