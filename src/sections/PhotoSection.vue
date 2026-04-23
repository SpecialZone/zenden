<script setup lang="ts">
import { Swiper, SwiperSlide } from "swiper/vue";
import { Navigation } from "swiper/modules";

import "swiper/css";
import "swiper/css/navigation";

const images = ["/3.jpg", "/4.jpg", "/5.jpg", "/6.jpg", "/2.jpg"];
const modules = [Navigation];
</script>

<template>
  <div class="photos">
    <!-- <img src="/OVC.png" /> -->
    <Swiper :spaceBetween="20" :slidesPerView="1" navigation :modules="modules">
      <SwiperSlide v-for="img in images" :key="img">
        <img :src="img" style="width: 100%" />
      </SwiperSlide>
    </Swiper>
  </div>
</template>

<style scoped lang="css">
.photos {
  background-color: rgb(12, 12, 12);
  width: 100%;
}
img {
  width: 100%;
}
@media (min-width: 800px) {
  .photos {
    width: 50%;
  }
}
</style>
