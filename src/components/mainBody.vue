<template lang="">
  <div class="body-container">
    <v-container class="pa-16">
      <h1 class="text-h6 text-center">Full Service Digital Marketing Agency</h1>
      <div class="dividerSvg d-flex justify-center mt-3">
        <img src="DividerSvg.svg" alt="" />
      </div>
      <div class="pWrapper d-flex justify-center" style="font-size: 12px">
        <p class="text-center mt-3" style="width: 30rem">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam,
          purus sit amet luctus venenatis, lectus magna fringilla urna,
          porttitor rhoncus dolor purus non enim praes
        </p>
      </div>
      <v-row>
        <v-col v-for="card in cards" :cols="3" :xs="2" align="center">
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
    <div class="text-wrapper-2 d-flex justify-center mt-n4 pa-3">
      <div
        class="text-center d-flex justify-space-between"
        style="width: 27rem"
      >
        <v-btn
          rounded
          color="#FBA60B"
          dark
          style="width: 200px; font-size: 12px; color: white"
        >
          Free Seo Consultation
        </v-btn>
        <v-btn
          rounded
          color="#4942A2"
          dark
          style="width: 200px; font-size: 12px; color: white"
        >
          Request afree quote
        </v-btn>
      </div>
    </div>
    <div class="marquee">
      <div class="marquee-container">
        <img
          class="first-marquee"
          src="sponsor.svg"
          width="172"
          height="79"
          alt=""
        />
        <img src="sponsor.svg" width="172" height="79" alt="" />
        <img src="sponsor.svg" width="172" height="79" alt="" />
        <img src="sponsor.svg" width="172" height="79" alt="" />
        <img src="sponsor.svg" width="172" height="79" alt="" />
        <img src="sponsor.svg" width="172" height="79" alt="" />
      </div>
    </div>
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
.marquee-container img {
  animation: bannermove 1s linear infinite;
  white-space: nowrap;
}
.marquee-container {
  width: 100%;
  overflow: hidden;
}
.marquee {
  overflow: hidden;
  display: flex;
  justify-content: center;
}
@keyframes "bannermove" {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100%);
  }
}
</style>
