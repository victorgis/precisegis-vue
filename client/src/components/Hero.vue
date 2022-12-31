<template>
  <div>
    <!-- ======= hero Section ======= -->
    <section id="hero">
      <div class="hero-content" data-aos="fade-up">
        <h2>Digital & <span>Geospatial</span><br />Solutions Company</h2>
        <div>
          <a href="#about" class="btn-get-started scrollto">Get Started</a>
          <a href="#services" class="btn-projects scrollto">Our Services</a>
        </div>
      </div>

      <swiper
        :spaceBetween="30"
        :centeredSlides="true"
        :autoplay="{
          delay: 2500,
        }"
        :pagination="{
          clickable: true,
        }"
        :modules="modules"
        class="mySwiper hero-slider swiper"
      >
        <swiper-slide
          ><img src="../assets/img/hero-carousel/1.jpg" /></swiper-slide
        ><swiper-slide
          ><img src="../assets/img/hero-carousel/2.jpg" /></swiper-slide
        ><swiper-slide
          ><img src="../assets/img/hero-carousel/3.jpg" /></swiper-slide
        ><swiper-slide
          ><img src="../assets/img/hero-carousel/4.jpg"
        /></swiper-slide>
        <swiper-slide
          ><img src="../assets/img/hero-carousel/5.jpg"
        /></swiper-slide>
      </swiper>
    </section>
    <!-- End Hero Section -->
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay, Pagination, Navigation } from "swiper";

export default {
  name: "Hero",
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination, Navigation],
    };
  },
};
</script>

<style scoped>
#hero {
  width: 100%;
  height: 60vh;
  position: relative;
  background: url("../assets/img/hero-carousel/1.jpg") no-repeat;
  background-size: cover;
  padding: 0;
}
#hero .hero-content {
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  right: 0;
  z-index: 10;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
}
#hero .hero-content h2 {
  color: #0c2e8a;
  margin-bottom: 30px;
  font-size: 64px;
  font-weight: 700;
}
#hero .hero-content h2 span {
  color: #50d8af;
  text-decoration: underline;
}
@media (max-width: 767px) {
  #hero .hero-content h2 {
    font-size: 34px;
    padding-left: 10px;
    padding-right: 10px;
  }
}
#hero .hero-content .btn-get-started,
#hero .hero-content .btn-projects {
  font-family: "Raleway", sans-serif;
  font-size: 15px;
  font-weight: bold;
  letter-spacing: 1px;
  display: inline-block;
  padding: 10px 32px;
  border-radius: 2px;
  transition: 0.5s;
  margin: 10px;
  color: #fff;
}
#hero .hero-content .btn-get-started {
  background: #0c2e8a;
  border: 2px solid #0c2e8a;
}
#hero .hero-content .btn-get-started:hover {
  background: none;
  color: #0c2e8a;
}
#hero .hero-content .btn-projects {
  background: #50d8af;
  border: 2px solid #50d8af;
}
#hero .hero-content .btn-projects:hover {
  background: none;
  color: #50d8af;
}
#hero .hero-slider {
  z-index: 8;
  height: 60vh;
}
#hero .hero-slider::before {
  content: "";
  background-color: rgba(255, 255, 255, 0.7);
  position: absolute;
  height: 100%;
  width: 100%;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
  z-index: 7;
}
#hero .hero-slider .swiper-slide {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  transition-property: opacity;
}

.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>