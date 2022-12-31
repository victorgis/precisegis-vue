<template>
  <main id="main">
    <!-- ======= About Section ======= -->
    <section id="about">
      <div class="container" data-aos="fade-up">
        <div class="row">
          <div class="col-lg-6 about-img">
            <img src="../assets/img/about-img.jpg" alt="" />
          </div>

          <div class="col-lg-6 content">
            <h2 class="heading">Who We Are. What We Do</h2>
            <h3 class="sub-heading">
              Geospatial & Digital Solutions Company, specializing creating
              innovative digital solutions for everyone, everywhere!
            </h3>

            <ul class="info">
              <li>
                <i class="bi bi-check-circle"></i> Get your websites built in
                less than 72 hours.
              </li>
              <li>
                <i class="bi bi-check-circle"></i> Build your digital &
                multimedia solutions.
              </li>
              <li>
                <i class="bi bi-check-circle"></i> Create GIS maps & web apps.
              </li>
              <li>
                <i class="bi bi-check-circle"></i> Get GIS training via our
                Precise GIS Academy.
              </li>
              <li>
                <i class="bi bi-check-circle"></i> Get Digital Skills & Courses
                from our Academy.
              </li>
              <li>
                <i class="bi bi-check-circle"></i> Purchase digital products via
                our store page.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!-- End About Section -->

    <!-- ======= Services Section ======= -->
    <section id="services">
      <div class="container" data-aos="fade-up">
        <div class="section-header">
          <h2 class="heading">Services</h2>
          <p class="sub-heading">
            we are bringing digital solutions for everyone, everywhere!
          </p>
        </div>

        <div class="row gy-4">
          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="200">
            <div class="box">
              <div class="icon">
                <a href="#contactus"><i class="bi bi-globe"></i></a>
              </div>
              <h4 class="title"><a href="#contactus">Web Development</a></h4>
              <p class="description">
                Without a website, people may question your legitimacy as a
                business. Having a website is an opportunity to make a great
                first impression and give people comfort that you’re a real
                business.
              </p>
            </div>
          </div>

          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="400">
            <div class="box">
              <div class="icon">
                <a href="#contactus"><i class="bi bi-menu-app"></i></a>
              </div>
              <h4 class="title">
                <a href="#contactus">Multimedia Solutions</a>
              </h4>
              <p class="description">
                Stay ahead of the technological curve by being proactive. Create
                innovative Multimedia solutions to bring about real-world
                solutions
              </p>
            </div>
          </div>

          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="300">
            <div class="box">
              <div class="icon">
                <a href="#contactus"><i class="bi bi-bar-chart"></i></a>
              </div>
              <h4 class="title">
                <a href="#contactus"
                  >Google Business Listing & Search Optimization</a
                >
              </h4>
              <p class="description">
                Get your business listed on Google and you’re 70% more likely to
                attract potential customers for on-site location visits. Also,
                your Google Map listing can pull in up to 35% clicks to your
                website.
              </p>
            </div>
          </div>

          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
            <div class="box">
              <div class="icon">
                <a href="#contactus"><i class="bi bi-map"></i></a>
              </div>
              <h4 class="title">
                <a href="#contactus">GIS Maps, WebApps & Spatial Analysis</a>
              </h4>
              <p class="description">
                A full-service GIS and Remote Sensing team are ready for your
                need, with excellence in Data Collection, Image Interpretation
                and Spatial Analysis.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Services Section -->

    <!-- ======= Services Section ======= -->
    <section id="services">
      <div id="nft" class="container" data-aos="fade-up">
        <div class="section-header">
          <h2 class="heading">NFTs</h2>
          <p class="sub-heading">
            A non-fungible token (NFT) is a non-interchangeable unit of data
            stored on a blockchain, a form of digital ledger, that can be sold
            and traded.
          </p>
        </div>

        <div class="row gy-4">
          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
            <div class="box">
              <div class="icon">
                <a href="https://opensea.io/precisegis" target="_blank"
                  ><i class="bi bi-coin"></i
                ></a>
              </div>
              <h4 class="title">
                <a href="https://opensea.io/precisegis" target="_blank"
                  >Take a look on our NFT collections at OpenSeas</a
                >
              </h4>
              <p class="description">
                Discover, collect, and re-sell our extraordinary NFTs OpenSea is
                the world's first and largest NFT marketplace.
              </p>
            </div>
          </div>

          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="200">
            <div class="box">
              <div class="icon">
                <a href="comingsoon.html" target="_blank"
                  ><i class="bi bi-cash-coin"></i
                ></a>
              </div>
              <h4 class="title">
                <a href="comingsoon.html" target="_blank"
                  >Take a look on our NFT collections at Binance NFT
                  Marketplace</a
                >
              </h4>
              <p class="description">
                Binance NFT Marketplace brings artists and creators together on
                a single platform. Buy premium and exclusive NFTs created by
                Precise GIS cartographers & artists
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Services Section -->

    <!-- ======= Clients Section ======= -->
    <section id="clients">
      <div class="container" data-aos="fade-up">
        <div class="section-header">
          <h2 class="heading">Clients</h2>
          <p class="sub-heading">
            We are solving real-world problems digitally. We are creating
            innovative digital solutions for everybody, everywhere!
          </p>
        </div>

        <div
          class="clients-slider swiper"
          data-aos="fade-up"
          data-aos-delay="100"
        >
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
            class="mySwiper"
          >
            <swiper-slide class="align-items-center"
              ><img
                class="img-fluid"
                src="../assets/img/clients/client-1.png" /></swiper-slide
            ><swiper-slide
              ><img
                class="img-fluid"
                src="../assets/img/clients/client-2.png" /></swiper-slide
            ><swiper-slide
              ><img
                class="img-fluid"
                src="../assets/img/clients/client-3.png" /></swiper-slide
            ><swiper-slide
              ><img class="img-fluid" src="../assets/img/clients/client-4.png"
            /></swiper-slide>
            <swiper-slide
              ><img class="img-fluid" src="../assets/img/clients/client-5.png"
            /></swiper-slide>
            <swiper-slide
              ><img class="img-fluid" src="../assets/img/clients/client-6.png"
            /></swiper-slide>
            <swiper-slide
              ><img class="img-fluid" src="../assets/img/clients/client-7.png"
            /></swiper-slide>
          </swiper>

          <!-- <div class="swiper-wrapper align-items-center">
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-1.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-2.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-3.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-4.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-5.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-6.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-7.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="swiper-slide">
                <img
                  src="../assets/img/clients/client-7.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
            </div>
            <div class="swiper-pagination"></div> -->
        </div>
      </div>
    </section>
    <!-- End Clients Section -->

    <!-- ======= Testimonials Section ======= -->
    <section id="testimonials">
      <div class="container" data-aos="fade-up">
        <div class="section-header">
          <h2 class="heading">Testimonials</h2>
          <p class="sub-heading">
            A statement from a past customer that describes how a product or
            service helped them.
          </p>
        </div>

        <div
          class="testimonials-slider swiper"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="testimonial-item">
                <p>
                  <img
                    src="../assets/img/quote-sign-left.png"
                    class="quote-sign-left"
                    alt=""
                  />
                  I love their remote training. It's cool and you can get the
                  video of your training sent to you, very cool!
                  <img
                    src="../assets/img/quote-sign-right.png"
                    class="quote-sign-right"
                    alt=""
                  />
                </p>
                <img
                  src="../assets/img/testimonial-1.jpg"
                  class="testimonial-img"
                  alt=""
                />
                <h3>Adamu El-Oji</h3>
                <h4>Veterinary Doctor</h4>
              </div>
            </div>
            <!-- End testimonial item -->

            <div class="swiper-slide">
              <div class="testimonial-item">
                <p>
                  <img
                    src="../assets/img/quote-sign-left.png"
                    class="quote-sign-left"
                    alt=""
                  />
                  They’re very good at what they do and the best in Nigeria I
                  have worked with at the moment.
                  <img
                    src="../assets/img/quote-sign-right.png"
                    class="quote-sign-right"
                    alt=""
                  />
                </p>
                <img
                  src="../assets/img/testimonial-2.jpg"
                  class="testimonial-img"
                  alt=""
                />
                <h3>Ediale Priscilla</h3>
                <h4>Petroleum Engineer</h4>
              </div>
            </div>
            <!-- End testimonial item -->

            <div class="swiper-slide">
              <div class="testimonial-item">
                <p>
                  <img
                    src="../assets/img/quote-sign-left.png"
                    class="quote-sign-left"
                    alt=""
                  />
                  They build great websites and web apps. Web mapping
                  applications. Very excellent guys.
                  <img
                    src="../assets/img/quote-sign-right.png"
                    class="quote-sign-right"
                    alt=""
                  />
                </p>
                <img
                  src="../assets/img/testimonial-3.jpg"
                  class="testimonial-img"
                  alt=""
                />
                <h3>Yeremi Akpan</h3>
                <h4>Backend Developer</h4>
              </div>
            </div>
            <!-- End testimonial item -->

            <div class="swiper-slide">
              <div class="testimonial-item">
                <p>
                  <img
                    src="../assets/img/quote-sign-left.png"
                    class="quote-sign-left"
                    alt=""
                  />
                  Precise GIS is one of the topnotch GIS firms that offers a
                  great deal of service for all Geospatial solutions.
                  <img
                    src="../assets/img/quote-sign-right.png"
                    class="quote-sign-right"
                    alt=""
                  />
                </p>
                <img
                  src="../assets/img/testimonial-4.jpg"
                  class="testimonial-img"
                  alt=""
                />
                <h3>Luwizatu Adamu</h3>
                <h4>Data Analyst</h4>
              </div>
            </div>
            <!-- End testimonial item -->

            <div class="swiper-slide">
              <div class="testimonial-item">
                <p>
                  <img
                    src="../assets/img/quote-sign-left.png"
                    class="quote-sign-left"
                    alt=""
                  />
                  I worked with them on a project, they're very professional.
                  Cool one guys!
                  <img
                    src="../assets/img/quote-sign-right.png"
                    class="quote-sign-right"
                    alt=""
                  />
                </p>
                <img
                  src="../assets/img/testimonial-5.jpg"
                  class="testimonial-img"
                  alt=""
                />
                <h3>John Midas</h3>
                <h4>Product Manager</h4>
              </div>
            </div>
            <!-- End testimonial item -->
          </div>
          <div class="swiper-pagination"></div>
        </div>
      </div>
    </section>
    <!-- End Testimonials Section -->

    <!-- ======= Call To Action Section ======= -->
    <section id="call-to-action">
      <div class="container" data-aos="zoom-out">
        <div class="row">
          <div class="col-lg-9 text-center text-lg-start">
            <h3 class="cta-title">Call To Action</h3>
            <p class="cta-text">
              It’s no secret that Precise GIS puts out some of the best tech
              solutions around, rather than spending more time search, let's end
              your search with us.
            </p>
          </div>
          <div class="col-lg-3 cta-btn-container text-center">
            <a class="cta-btn align-middle" href="#contact">Call To Action</a>
          </div>
        </div>
      </div>
    </section>
    <!-- End Call To Action Section -->

    <Contact />
  </main>
  <!-- End #main -->
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay, Pagination, Navigation } from "swiper";
import Contact from "./Contact.vue";

export default {
  name: "Main",
  components: {
    Swiper,
    SwiperSlide,
    Contact,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination, Navigation],
    };
  },
};
</script>