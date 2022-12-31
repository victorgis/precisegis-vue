<template>
  <!-- ======= Contact Section ======= -->
  <section id="contact">
    <div class="container" data-aos="fade-up">
      <div class="section-header">
        <h2 class="heading">Contact Us</h2>
        <p class="sub-heading">
          Dear Visitor, you can contact our team with general questions about
          our products & Services, or about the website, by using the form
          below.
        </p>
      </div>

      <div class="row contact-info">
        <div class="col-md-4">
          <div class="contact-address">
            <i class="bi bi-geo-alt"></i>
            <h3>Address</h3>
            <address>3 Green Springs Estate Rd, Uyo 520102, NG</address>
          </div>
        </div>

        <div class="col-md-4">
          <div class="contact-phone">
            <i class="bi bi-phone"></i>
            <h3>Phone Number</h3>
            <p><a href="tel:+2349077421323">+234 907 7421 323</a></p>
          </div>
        </div>

        <div class="col-md-4">
          <div class="contact-email">
            <i class="bi bi-envelope"></i>
            <h3>Email</h3>
            <p>
              <a href="mailto:precisegis@gmail.com" target="_blank"
                >precisegis@gmail.com</a
              >
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="container mb-4">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d496.84523769189667!2d7.964739065018844!3d4.979188674522308!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x1e1dac76d7501988!2sPrecise%20GIS%20LTD!5e0!3m2!1sen!2sng!4v1646264807537!5m2!1sen!2sng"
        width="100%"
        height="380"
        frameborder="0"
        style="border: 0"
        allowfullscreen
      ></iframe>
    </div>

    <div class="container" id="contactus">
      <div class="form">
        <form method="POST" action="send" class="php-email-form">
          <div class="row">
            <div class="form-group col-md-6">
              <input
                v-model="user.name"
                type="text"
                name="name"
                class="form-control"
                id="name"
                placeholder="Your Name"
                required
              />
            </div>
            <div class="form-group col-md-6 mt-3 mt-md-0">
              <input
                v-model="user.email"
                type="email"
                class="form-control"
                name="email"
                id="email"
                placeholder="Your Email"
                required
              />
            </div>
          </div>
          <div class="form-group mt-3">
            <input
              v-model="user.subject"
              type="text"
              class="form-control"
              name="subject"
              id="subject"
              placeholder="Subject"
              required
            />
          </div>
          <div class="form-group mt-3">
            <textarea
              v-model="user.message"
              class="form-control"
              name="message"
              rows="5"
              placeholder="Message"
              required
            ></textarea>
          </div>

          <div class="my-3">
            <div class="loading">Loading</div>
            <div class="error-message"></div>
            <div class="sent-message">
              Your message has been sent. Thank you!
            </div>
          </div>

          <div class="text-center">
            <button type="submit" @click="sendEmail">
              <!-- <span
                v-if="loader"
                class="spinner-border spinner-border-sm"
                role="status"
                aria-hidden="true"
              ></span -->
              >Send Message
            </button>
          </div>
        </form>
      </div>
    </div>
  </section>
  <!-- End Contact Section -->
</template>

<script>
import axios from "axios";

export default {
  name: "Contact",
  data() {
    return {
      user: {
        name: "",
        email: "",
        // phone: "",
        subject: "",
        message: "",
      },
      loader: false,
    };
  },
  methods: {
    async sendEmail(e) {
      e.preventDefault();
      this.loader = true;

      // const data = this.user;
      try {
        // debugger;
        await axios.post(
          "https://growthhubonline.org/api/sendemail",
          this.user
        );

        // console.log("This user" + this.user);
        // alert("Sent");
        this.loader = false;
      } catch (err) {
        alert("Something Went Wrong");
        this.loader = false;
      }
    },
  },
};
</script>