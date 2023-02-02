<template lang="">
  <div>
    <v-container>
      <h1 class="text-h4 text-center pt-8">Latest News</h1>
      <div class="dividerSvg d-flex justify-center mt-3">
        <img src="DividerSvg.svg" alt="" />
      </div>
      <div class="pWrapper d-flex justify-center" style="font-size: 15px">
        <p class="text-center mt-3" style="width: 42rem">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam,
          purus sit amet luctus venenatis, lectus magna fringilla urna,
          porttitor rhoncus dolor purus non enim praes
        </p>
      </div>
      <v-row>
        <v-col v-for="info in infos" :cols="6" :xs="2" align="center">
          <div class="news-cards mt-8">
            <div class="news-card">
              <div class="square"></div>
              <div class="news-card-text">
                <p class="text-caption">June 30, 2022</p>
                <h1 class="text-h6">{{ info.title }}</h1>
                <p class="text-subtitle-1">
                  Lorem ipsum dolor sit amet,<br />
                  consectetur adipiscing elit ut aliquam
                </p>
                <v-btn text flat class="text-caption"> continue reading </v-btn>
              </div>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  data: () => ({
    infos: [
      {
        title: "A 5-Point Checklist",
      },
      {
        title: "Tools Your SEO Expert",
      },
      {
        title: "Emoji Search Optimization",
      },
      {
        title: "SEO in one package",
      },
    ],
  }),
};
</script>
<style lang="scss">
.news-cards {
  margin-left: 70px;
}
.news-card {
  width: 530px;
  height: 178px;
  display: flex;
  justify-content: space-between;
}
.square {
  width: 160px;
  height: 130px;
  background-color: grey;
  border-radius: 20px;
}
.news-card-text {
  width: 360px;
  text-align: left;
}
</style>
