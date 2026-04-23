<script setup lang="ts">
import VideoSection from "./sections/VideoSection.vue";
import LogoSection from "./sections/LogoSection.vue";
import AboutSection from "./sections/AboutSection.vue";
import PhotoSection from "./sections/PhotoSection.vue";
import ListenSection from "./sections/ListenSection.vue";
import ContactSection from "./sections/ContactSection.vue";
import LiveSection from "./sections/LiveSection.vue";
</script>

<template>
  <div class="rubik-font">
    <LogoSection />
    <VideoSection />
    <div class="responsive-block wrapper">
      <AboutSection />
      <PhotoSection />
    </div>
    <ListenSection />
    <LiveSection />
    <ContactSection />
  </div>
</template>

<style lang="css" scoped>
.responsive-block {
  display: block;
}
@media (min-width: 800px) {
  .responsive-block {
    display: flex;
  }
}
</style>
