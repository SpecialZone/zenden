<script setup lang="ts"></script>
<template>
  <div class="about" id="about">
    <div class="inner-about">
      Zenden Greenpurp is an avant-progressive metal band from Reading
      experimenting with music through chaotic compositions, theatrical vocals
      and intense performances.
      <!-- <p><b>Zenden Greenpurp</b> is a musical anomaly from Reading, UK.</p>
      <p>
        Imagine an experimental rock outfit that sounds like a mad scientist
        created a mutant creature by disrupting the DNA of metal, prog,
        psychedelia and punk. The Purp warp genres with a ferocious
        unpredictability that defies classification.
      </p>
      <ul>
        <li>Frantic time signature changes</li>
        <li>Manic intensity</li>
        <li>Theatrical madness</li>
        <li>Savage melodic maelstroms</li>
      </ul>
      <br />
      <p>Currently booking gigs.</p> -->
    </div>
  </div>
</template>

<style scoped lang="css">
.about {
  color: white;
  line-height: 35px;
}
.inner-about {
  padding: 85px 70px 70px 70px;
  font-size: 24px;
  text-align: center;
}
.about p {
  margin-bottom: 30px;
}
ul {
  list-style: none;
}
li {
  margin-bottom: 5px;
}
ul li:before {
  content: "✓";
  margin-right: 15px;
}
ul li:before {
  color: rgb(196, 101, 191);
}
@media (min-width: 800px) {
  .about {
    width: 50%;
  }
}
</style>
