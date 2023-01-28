<template lang="">
  <div class="body-container">
    <v-container class="pa-16">
      <v-row>
        <v-col v-for="card in cards" :cols="3" align="center">
          <v-hover v-slot="{ hover }">
            <v-card
              outlined
              height="300"
              max-width="220"
              class="mt-8 d-flex flex-column justify-start"
              :class="{ 'on-hover': hover }"
            >
              <v-img
                :src="card.icon"
                max-height="112"
                max-width="112"
                justify-start
                class="ma-3"
              ></v-img>
              <div
                class="cardText"
                style="width: 9rem; text-align: left; margin-left: 20px"
              >
                <h1 style="font-size: 16px">{{ card.title }}</h1>
              </div>
              <v-card-text style="font-size: 10px; text-align: left">{{
                card.subtitle
              }}</v-card-text>
              <v-card-actions>
                <v-btn text color="purple accent-4" @click="reveal = true">
                  Learn More
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-hover>
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
        icon: "Card-1.svg",
        title: "Digital PR Link-Building",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-2.svg",
        title: "Link Building & Content",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-3.svg",
        title: "Maps Search Optimization",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-4.svg",
        title: "Big Data Analysis",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-5.svg",
        title: "Custom Email Design",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-6.svg",
        title: "Monitoring Ranking",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-7.svg",
        title: "Code Optimization",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
      {
        icon: "Card-8.svg",
        title: "Nap Syndication",
        subtitle:
          "Lorem ipsum dolor sit amet adipiscing elit ut aliquam, purus sit amet luctus venenatis",
      },
    ],
  }),
};
</script>
<style lang="scss">
.v-card .v-card-text {
  line-height: 0.8rem;
}
.v-card.on-hover {
  background-color: red;
}
</style>
