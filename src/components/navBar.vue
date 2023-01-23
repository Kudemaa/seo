<template lang="">
  <div class="nav-container">
    <div class="nav-sections">
      <div class="nav-section1">
        <img src="../assets/Logo.svg" alt="" />
      </div>
      <div class="nav-section2">
        <ul class="list-items">
          <li><a href="#">HOME</a></li>
          <li><a href="#">PAGES</a></li>
          <li><a href="#">SERVICES</a></li>
          <li><a href="#">CASE STUDIES</a></li>
          <li><a href="#">CONTACT</a></li>
        </ul>
      </div>
      <div class="nav-section3">
        <img src="../assets/search.svg" alt="" />
        <img src="../assets/items.svg" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.nav-container {
  padding-top: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.nav-sections {
  display: flex;
  justify-content: space-between;
  width: 70rem;
  align-items: center;
}
.nav-section1 img {
  padding-top: 10px;
}
.nav-section2 {
  width: 25rem;
}
.nav-section3 {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 7rem;
}
.nav-section3 img {
  cursor: pointer;
}
.list-items {
  display: flex;
  justify-content: space-between;
  list-style: none;
  align-items: center;
}
.list-items li a {
  text-decoration: none;
  color: white;
  font-size: 12px;
}
</style>
