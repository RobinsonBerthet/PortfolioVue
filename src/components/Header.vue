<template>
  <header>
    <div class="page-banner home-banner">
      <div class="container h-100">
        <div class="row align-items-center h-100">
          <div class="col-lg-6 py-3 wow fadeInUp">
            <p
              class="text-green-600 hover:text-green-500 text-2xl lg:text-4xl font-medium lg:font-semibold mb-5 lg:leading-normal leading-snug">
              Bonjour, Je suis Robinson
              <br />
              Étudiant en développement Informatique
            </p>
            <p
              class="hidden lg:block text-2xl mb-5">
              Je suis passioné par le développement depuis quelques années et j'adore apprendre de nouvelles choses
            </p>

            <router-link
              to="/apropos"
              name="fade"
              class="btn btn-outline border text-secondary">
              A propos
            </router-link>
            <!-- <a
              href="#"
              class="btn btn-primary btn-split ml-2">
              Télécharger mon CV
              <div class="fab"><span class="mai-play"></span></div>
            </a> -->
            <br>
            <br>
            <a href="https://www.linkedin.com/in/robinson-berthet-846858231/" class="btnLinkedin">
              <img src="/images/linkedin.png" class ="imgLinkedin"/>
              <p class="flex-1 ml-2 whitespace-nowrap">Linkedin</p>
            </a>
            
              

          </div>
          <div class="col-lg-6 wow zoomIn">
            <div
              class="m-3 lg:m-3 p-1 lg:p-5">
              <lottie-player
                src="https://assets2.lottiefiles.com/packages/lf20_gnb0jsok.json"
                background="transparent"
                speed="1"
                style="max-width: 500px; max-height: 500px"
                autoplay></lottie-player>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import { directive as motion } from "@vueuse/motion";

export default {};
</script>

<style></style>
