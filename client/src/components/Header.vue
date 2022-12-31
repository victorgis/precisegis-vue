<template>
  <div>
    <!-- ======= Top Bar ======= -->
    <section id="topbar" class="d-flex align-items-center">
      <div
        class="
          container
          d-flex
          justify-content-center justify-content-md-between
        "
      >
        <div class="contact-info d-flex align-items-center">
          <i class="bi bi-envelope d-flex align-items-center"
            ><a href="mailto:precisegis@gmail.com" target="_blank"
              >precisegis@gmail.com</a
            ></i
          >
          <i class="bi bi-phone d-flex align-items-center ms-4"
            ><span><a href="tel: +2349077421323">+234 907 7421 323</a></span></i
          >
        </div>
        <div class="social-links d-none d-md-flex align-items-center">
          <a
            href="https://www.twitter.com/precisegis"
            target="_blank"
            class="twitter"
            ><i class="bi bi-twitter"></i
          ></a>
          <a
            href="https://www.facebook.com/precisegis"
            target="_blank"
            class="facebook"
            ><i class="bi bi-facebook"></i
          ></a>
          <a
            href="https://www.instagram.com/precisegis2"
            target="_blank"
            class="instagram"
            ><i class="bi bi-instagram"></i
          ></a>
          <a
            href="https://www.linkedin.com/company/precise-ng"
            target="_blank"
            class="linkedin"
            ><i class="bi bi-linkedin"></i
          ></a>
        </div>
      </div>
    </section>
    <!-- End Top Bar-->

    <!-- ======= Header ======= -->
    <header id="header" class="d-flex align-items-center">
      <div class="container d-flex justify-content-between">
        <div id="logo">
          <a href="/"><img src="../assets/img/logo.svg" alt="" /></a>
        </div>

        <nav id="navbar" class="navbar">
          <ul>
            <li>
              <a class="nav-link scrollto active" href="index.html">Home</a>
            </li>
            <li><a class="nav-link scrollto" href="#about">About</a></li>
            <li><a class="nav-link scrollto" href="#services">Services</a></li>
            <li><a class="nav-link scrollto" href="#nft">NFTs</a></li>
            <li>
              <a class="nav-link scrollto" href="store.html" target="_blank"
                >Store</a
              >
            </li>
            <li>
              <a
                class="nav-link scrollto"
                href="https://www.medium.com/@precisegis"
                target="_blank"
                >Blog</a
              >
            </li>
            <!-- <li><a class="nav-link scrollto" href="#team">Team</a></li> -->
            <li class="dropdown">
              <a href="#"
                ><span>Careers & More</span> <i class="bi bi-chevron-down"></i
              ></a>
              <ul>
                <li>
                  <a href="contact.html#contactus" target="_blank">Careers</a>
                </li>
                <li><a href="courses.html" target="_blank">Courses</a></li>
                <li>
                  <a href="publications.html" target="_blank">Publications</a>
                </li>
                <!-- <li><a href="#">Drop Down 4</a></li> -->
              </ul>
            </li>
            <li>
              <a
                class="nav-link scrollto"
                href="http://precisegis.com.ng/contact"
                target="_blank"
                >Contact</a
              >
            </li>
          </ul>
          <i class="bi bi-list mobile-nav-toggle"></i>
        </nav>
        <!-- .navbar -->
      </div>
    </header>
    <!-- End Header -->
  </div>
</template>

<script>
export default {
  name: "Headers",
};
</script>

<style scoped>
#header #logo {
  /* max-height: 40px; */
  /* height: 30px; */
  width: 118px;

  margin: auto 0px;
}
</style>