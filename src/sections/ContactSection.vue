<script setup lang="ts"></script>
<template>
  <div class="contact-section flex">
    <div class="socials">
      <div>
        <a href="https://www.facebook.com/ZendenGreenpurp"
          ><i class="fa-brands fa-square-facebook"></i
        ></a>
        <a
          href="https://www.instagram.com/zenden_greenpurp?igsh=M3hsbHExYWQwYmcz"
          ><i class="fa-brands fa-square-instagram"></i
        ></a>
        <a
          href="https://open.spotify.com/artist/1oqqiAC4EqHLxDCQsmIHxy?si=qG4vF85NSVqWF_Jp74xABg"
          ><i class="fa-brands fa-spotify"></i
        ></a>
      </div>
      <div>
        <a href="https://zendengreenpurp.bandcamp.com/album/quadrillionth"
          ><i class="fa-brands fa-bandcamp"></i
        ></a>
        <a href="https://www.youtube.com/channel/UCtwS5L3rQRmx0n7DXFZmPqQ"
          ><i class="fa-brands fa-youtube"></i
        ></a>
        <a href="https://music.apple.com/us/artist/zenden-greenpurp/1633751713"
          ><i class="fa-brands fa-apple"></i
        ></a>
      </div>
    </div>
  </div>
</template>

<style scoped lang="css">
.socials {
  justify-content: center;
  margin: 0 auto;
}
.contact-section {
  padding: 70px;
  color: white;
}
.socials div {
  text-align: center;
  margin-bottom: 30px;
}
a {
  color: white;
  font-size: 40px;
  padding: 15px;
}
a:hover {
  opacity: 0.5;
}
@media (min-width: 800px) {
  .socials {
    display: flex;
  }
}
</style>
