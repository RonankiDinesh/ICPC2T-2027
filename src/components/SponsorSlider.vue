<template>
  <div class="sponsor-section">
    <h3 class="title">Our Technical Sponsors</h3>

    <div class="slider">
      <div class="slide-track">
        <div class="slide" v-for="(img, index) in images" :key="index">
          <img :src="img" alt="sponsor" />
        </div>

        <!-- duplicate for infinite effect -->
        <div class="slide" v-for="(img, index) in images" :key="'dup'+index">
          <img :src="img" alt="sponsor" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SponsorSlider",
  data() {
    return {
      images: [
        require("../assets/sponsor1.png"),
        require("../assets/sponsor2.png"),
        require("../assets/sponsor3.png"),
        require("../assets/sponsor4.png"),
      ],
    };
  },
};
</script>

<style scoped>
.sponsor-section {
  padding: 20px;
  background: #f8f9fa;
  text-align: center;
}

.title {
  margin-bottom: 15px;
  font-weight: bold;
}

/* Slider */
.slider {
  overflow: hidden;
  position: relative;
}

.slide-track {
  display: flex;
  width: calc(250px * 8);
  animation: scroll 20s linear infinite;
}

.slide {
  width: 250px;
  padding: 10px;
}

.slide img {
  width: 100%;
  height: 80px;
  object-fit: contain;
}

/* Animation */
@keyframes scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-50%);
  }
}
</style>