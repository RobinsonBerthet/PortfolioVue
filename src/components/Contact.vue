<template>
  <Navbar/>
  <div class="page-section">
    <div class="container">
      <div class="row align-items-center">
        <!-- <div class="col-lg-6 py-3 wow fadeInUp">
          <h2 class="title-section">Contact information</h2>
          <div class="divider"></div>
          <p>
            Great genius takes shape by contact with another great genius,
            <br />
            but, less by assimilation than by friction.
          </p>

          <ul class="contact-list">
            <li>
              <div class="icon"><span class="mai-map"></span></div>
              <div class="content">123 Main Street, Seoul, South Korea</div>
            </li>
            <li>
              <div class="icon"><span class="mai-mail"></span></div>
              <div class="content"><a href="#">aaron08889@gmail.com</a></div>
            </li>
            <li>
              <div class="icon"><span class="mai-phone-portrait"></span></div>
              <div class="content"><a href="#">+8210 5818 2222</a></div>
            </li>
          </ul>
        </div> -->
        <div class="">
          <div class="subhead">Contactez Moi</div>
          <div class="divider"></div>

          <form name="contact" method="POST" data-netlify="true">  
            <input type="hidden" name="contact" value="contact" />          
            <div class="py-2">
              <input type="text" class="form-control" placeholder="Votre Nom" name="name"/>
            </div>
            <div class="py-2">
              <input type="text" class="form-control" placeholder="Email" name="email"/>
            </div>
            <div class="py-2">
              <textarea
                rows="6"
                class="form-control"
                placeholder="Entrer un message" name="message"></textarea>
            </div>
            <div class="py-2">
              <button type="submit" class="btnEnvoyerContact">Envoyer</button>
            </div>
          </form>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
  <Footer :contact="contact" />
</template>

<script>
import Navbar from "./Navbar.vue";
import Footer from "./Footer.vue";

export default {
  name: "Contact",

  components: {
    Navbar: Navbar,
    Footer: Footer,
  },
};
</script>

<style></style>
