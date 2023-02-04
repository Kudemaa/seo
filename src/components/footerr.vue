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
        <div class="footer-top-second"></div>
      </div>
      <div class="footer-bottom-container"></div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.footer-container {
  width: 100vw;
  height: 400px;
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
  background-color: black;
  width: 100vw;
}
.footer-bottom-container {
  background-color: yellow;
  height: 100px;
}
</style>
