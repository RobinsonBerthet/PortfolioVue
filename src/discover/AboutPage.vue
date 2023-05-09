<template>
  <Navbar />

  <div class="hidden lg:block container mt-5">
    <div class="page-banner1">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-md-6">
          <nav aria-label="Breadcrumb">
            <ul class="breadcrumb justify-content-center py-0 bg-transparent">
              <li class="breadcrumb-item">
                <router-link to="/">Home</router-link>
              </li>
              <li class="breadcrumb-item active">About</li>
            </ul>
          </nav>
          <h1 class="text-center">About Us</h1>
        </div>
      </div>
    </div>
  </div>

  <About />
  <Services />

  <div class="bg-green-50 py-5 page-section">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="text-2xl mb-3">Qualités en tant que Développeur</div>
        <!-- <h3 class="title-section">
          <span class="">"Slow and Steady</span>
          Win The Rase"
        </h3> -->
        <div class="divider mx-auto"></div>
      </div>

      <div
        class="flex flex-col lg:flex-row items-center justify-evenly space-x-3 h-full text-left py-5">
        <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
            src="https://cdn.lordicon.com/dfxesbyu.json"
            trigger="hover"
            style="width: 150px; height: 150px"
            class="hidden lg:flex"></lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Auto-formation
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            L'auto-Formation est une qualité primordiale pour un Développeur car tout au long de sa carrière il doit apprendre de nouvelles choses, 
            il doit se mettre à jour par rapport aux nouvelles technologies qui sortent quotidiennement.
          </p>
        </div>

        <div
          class="bg-white rounded-xl mt-3 drop-shadow-md col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
            src="https://cdn.lordicon.com/xqgancly.json"
            trigger="hover"
            style="width: 150px; height: 150px"
            class="hidden lg:flex"></lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Persévérance
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            En tant que développeur, la persévérance est une qualité essentielle que je dois cultiver pour atteindre mes objectifs. 
            Elle ne doit pas être négligée, car sans elle, il est impossible de réaliser ce que l'on souhaite.
          </p>
        </div>

        <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
            src="https://cdn.lordicon.com/hursldrn.json"
            trigger="morph"
            style="width: 150px; height: 150px"
            class="hidden lg:flex"></lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Communication
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            La qualité de communication est cruciale dans le métier de développeur, 
            car elle permet de faciliter la collaboration, 
            de comprendre les besoins des clients et de transmettre efficacement les idées et les solutions techniques aux membres de l'équipe.
          </p>
        </div>
      </div>
    </div>
  </div>

  <Footer :blog="blog" />
</template>

<script>
import Navbar from "../components/Navbar";
import About from "../components/About";
import Services from "../components/Services";
import Footer from "../components/Footer";

export default {
  name: "About Page",
  data() {
    return {};
  },

  props: {
    blog: Array,
  },

  components: {
    Navbar,
    About,
    Services,
    Footer,
  },
};
</script>

<style></style>
