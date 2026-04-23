<script setup lang="ts"></script>

<template>
  <div class="video-section">
    <!-- <div class="wrapper">
      <img src="/OVC.png" />
    </div> -->

    <iframe
      id="video"
      src="https://www.youtube.com/embed/Pg_sYRPUCUs?autoplay=1&mute=1&controls=1&loop=1&playlist=Pg_sYRPUCUs&rel=0&playsinline=1"
      title="YouTube video player"
      frameborder="0"
      allow="autoplay; encrypted-media"
      allowfullscreen
    ></iframe>
  </div>
</template>

<style lang="css" scoped>
.video-section {
  background-color: rgba(0, 0, 0, 0.2);
}
img {
  width: 100%;
  max-width: 1200px;
  margin: 0px auto;
  display: block;
}
#video-frame {
  display: block;
  width: 100%;
  max-width: 1240px;
  margin: 0 auto;
}
#video {
  display: block;
  width: 100%;
  max-width: 1240px;
  margin: 0 auto;
  height: 700px;
}
</style>
