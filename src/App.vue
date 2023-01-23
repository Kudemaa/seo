<template>
  <v-app>
    <v-main>
      <hero />
    </v-main>
  </v-app>
</template>

<script>
import hero from "./components/hero.vue";

export default {
  name: "App",
  components: {
    hero,
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
