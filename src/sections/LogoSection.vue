<script setup lang="ts"></script>

<template>
  <div class="logo-section">
    <div class="wrapper flex">
      <img src="/logo.png" />
      <!-- <div class="links">
        <a href="#listen"><div class="link">LISTEN</div></a>
        <a href="#about"><div class="link">ABOUT</div></a>
        <div class="link">LIVE</div>
        <div class="link">CONTACT</div>
      </div> -->
    </div>
  </div>
</template>

<style lang="css">
.logo-section {
  height: 100px;
  position: sticky;
  top: 0;
  display: flex;
  background-image: url("../assets/bg.png");
  background-attachment: fixed;
  background-size: 100vw 100vh;
  z-index: 2;
}
.logo-section img {
  height: 100px;
  display: block;
  margin: 0 auto;
}
.links {
  height: 100%;
  display: none;
  color: white;
  margin-left: auto;
  margin-right: 50px;
}
.link {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100px;
  cursor: pointer;
}
.link:hover {
  background-color: rgba(256, 256, 256, 0.1);
  transition: background-color 0.3s;
}
a {
  color: white;
  text-decoration: none;
}
@media (min-width: 800px) {
  .links {
    display: flex;
  }
  .logo-section img {
    margin: 0 0;
  }
}
</style>
