<script setup lang="ts"></script>
<template>
  <div class="cool-bg">
    <div class="listen-section">
      <iframe
        style="border: 0; width: 100%; height: 120px"
        src="https://bandcamp.com/EmbeddedPlayer/album=3472224957/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/"
        seamless
        ><a href="https://zendengreenpurp.bandcamp.com/album/quadrillionth"
          >Quadrillionth by Zenden Greenpurp</a
        >
      </iframe>
      <iframe
        style="border: 0; width: 100%; height: 120px"
        src="https://bandcamp.com/EmbeddedPlayer/album=2113508430/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/"
        seamless
        ><a href="https://zendengreenpurp.bandcamp.com/album/darkspace-ltd"
          >Darkspace Ltd. by Zenden Greenpurp</a
        >
      </iframe>
      <iframe
        style="border: 0; width: 100%; height: 120px"
        src="https://bandcamp.com/EmbeddedPlayer/track=342777782/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/transparent=true/"
        seamless
        ><a
          href="https://zendengreenpurp.bandcamp.com/track/i-think-im-going-sane"
          >I Think I&#39;m Going Sane by Zenden Greenpurp</a
        >
      </iframe>
    </div>
  </div>
</template>

<style scoped lang="css">
.listen-section {
  max-width: 700px;
  margin: 0 auto;
}
iframe {
  display: block;
  margin: 30px auto;
}
.cool-bg {
  padding: 30px 15px;
  background-image: url("../assets/bg.png");
  background-attachment: fixed;
  background-size: 100vw 100vh;
}
</style>
