<script setup lang="ts"></script>

<template>
  <div class="live-section wrapper">
    <div class="upcoming">
      <br />
      <p><b>Upcoming shows</b></p>
      <p>23-May-2026 - Proteus Creation Space, Basingstoke</p>
      <p>27-May-2026 - The Purple Turtle, Reading</p>
      <p>31-Oct-2026 - Biggin Hall, Dover</p>
      <br />
      <br />
      <div>
        <p><b>Contact</b></p>
        <p>We are currently booking gigs.</p>
        <p>zendengreenpurp@gmail.com</p>
        <a href="mailto:zendengreenpurp@gmail.com">
          <button class="css-button-gradient--7 rubik-font">
            BOOK US NOW!
          </button>
        </a>
      </div>
    </div>
    <div class="live-photo">
      <img src="/live-photo.png" />
    </div>
  </div>
</template>

<style lang="css" scoped>
.live-section {
  color: white;
}
.css-button-gradient--7 {
  margin-top: 30px;
  min-width: 130px;
  height: 40px;
  color: #fff;
  padding: 5px 20px;
  font-weight: bold;
  font-size: 23px;
  cursor: pointer;
  transition: all 0.3s ease;
  position: relative;
  display: inline-block;
  outline: none;
  border-radius: 5px;
  border: none;
  background-size: 120% auto;
  background-image: linear-gradient(315deg, #c02425 0%, #f0cb35 75%);
  margin-bottom: 30px;
}
.css-button-gradient--7:hover {
  background-position: right center;
}
.css-button-gradient--7:active {
  top: 2px;
}
p {
  padding: 0 0 15px 0;
}
.upcoming {
  padding: 60px;
}
.live-photo img {
  display: block;
  margin: 0 auto;
  width: 70%;
  border: 3px solid rgb(64, 11, 126);
}
@media (min-width: 800px) {
  .live-section {
    display: flex;
  }
  .upcoming {
    width: 50%;
  }
  .live-photo {
    width: 50%;
    margin: 60px auto;
  }
}
</style>
