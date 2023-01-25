<template lang="">
  <div class="body-container">
    <v-container class="pa-16">
      <v-row dense>
        <v-col v-for="card in cards" :cols="3" align="center">
          <v-card outlined height="300" max-width="220" class="mt-8">
            <v-img :src="card.icon"></v-img>
            <v-card-title>{{ card.title }}</v-card-title>
            <v-card-text>{{ card.subtitle }}</v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  data: () => ({
    cards: [
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
      {
        icon: "../assets/cards/Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle: "Lorem Solem ipsum azul mo9ran a9chiche",
      },
    ],
  }),
};
</script>
<style lang="scss"></style>
