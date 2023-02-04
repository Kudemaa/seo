<template lang="">
  <div>
    <div class="footer-container mt-8">
      <div class="footer-top-container">
        <div class="footer-top-first">
          <div class="phone-container">
            <v-icon size="40" color="#F85D2F">mdi-phone-classic</v-icon>
            <div class="pc-text">
              <p class="text-caption" style="color: #626262">
                Mon to fri : 08H30 - 18H00
              </p>
              <p style="color: #ffffff" class="text-subtitle-1">
                + (92) 321 654 9876
              </p>
            </div>
          </div>
          <div class="email-container">
            <v-icon size="40" color="#41BC62">mdi-email-check</v-icon>
            <div class="pc-text">
              <p class="text-caption" style="color: #626262">
                Do you have a question?
              </p>
              <p style="color: #ffffff" class="text-subtitle-1">
                Company@mail.com
              </p>
            </div>
          </div>
          <div class="socials-container">
            <v-icon size="40" color="#1E76FE">mdi-vpn</v-icon>
            <div class="pc-text">
              <p class="text-caption" style="color: #626262">Socials Network</p>
              <div class="socials-icons">
                <v-icon color="#FFFFFF" class="mr-2">mdi-facebook</v-icon>
                <v-icon color="#FFFFFF" class="mr-2">mdi-twitter</v-icon>
                <v-icon color="#FFFFFF" class="mr-2">mdi-instagram</v-icon>
                <v-icon color="#FFFFFF" class="mr-2">mdi-snapchat</v-icon>
                <v-icon color="#FFFFFF" class="mr-2">mdi-reddit</v-icon>
                <v-icon color="#FFFFFF">mdi-telegram</v-icon>
              </div>
            </div>
          </div>
        </div>
        <div class="footer-top-second">
          <div class="first-column">
            <p class="text-h5 mb-3">Methdology</p>
            <img src="footerdivider.svg" alt="" />
            <p>On Page SEO</p>
            <p>Off Page SEO</p>
            <p>Thematic Keyword</p>
            <p>Web Development</p>
          </div>
          <div class="second-column">
            <p class="text-h5 mb-3">Useful Links</p>
            <img src="footerdivider.svg" alt="" />
            <p>Professional Team</p>
            <p>Testimonials</p>
            <p>Support</p>
            <p>Privacy Policy</p>
            <p>Press</p>
            <p>Why SEO MAtters</p>
          </div>
          <div class="third-column">
            <p class="text-h5 mb-3">Company</p>
            <img src="footerdivider.svg" alt="" />
            <p>Careers</p>
            <p>SEO Blog</p>
            <p>Sitemap</p>
            <p>Keyword Analytics</p>
          </div>
        </div>
      </div>
      <img src="footerline.svg" alt="" style="margin-left: 180px" />
      <div class="footer-bottom-container">
        <div class="bottom-first-column text-caption">
          <p>Copyright © 2022 Company.com . All rights reserved.</p>
        </div>
        <div class="bottom-second-column">
          <p>SERVICES</p>
          <p>FEATURES</p>
          <p>CASE STUDIES</p>
          <p>CONTACT</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.footer-container {
  width: 100vw;
  height: 430px;
  background-color: #1f242a;
}
.footer-top-container {
  height: 300px;
  display: flex;
}
.footer-top-first {
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.phone-container,
.email-container,
.socials-container {
  display: flex;
  margin-bottom: 20px;
  align-items: center;
}
.socials-icons > * {
  cursor: pointer;
}
.pc-text {
  width: 15rem;
  margin-left: 30px;
}
.footer-top-second {
  width: 100vw;
  color: white;
  display: flex;
}
.footer-bottom-container {
  color: white;
  height: 100px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}
.first-column,
.second-column,
.third-column {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-right: 30px;
  margin-top: 20px;
}
.first-column > *:not(:first-child),
.second-column > *:not(:first-child),
.third-column > *:not(:first-child) {
  margin-bottom: 17px;
  font-size: 12px;
  cursor: pointer;
}
.bottom-second-column {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 25rem;
}
.bottom-second-column > * {
  cursor: pointer;
}
</style>
