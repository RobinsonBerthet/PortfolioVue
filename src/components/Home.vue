<template>
  <Navbar />
  <Header />
  <Services />
  <About />

  <div class="bg-green-50 py-5 page-section">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="text-2xl mb-3">Qualités en tant que Développeur</div>
        <!-- <h3 class="title-section">
          <span>"Slow and Steady</span>
          Win The Rase"
        </h3> -->
        <div class="divider mx-auto"></div>
      </div>

      <div
        class="flex flex-col lg:flex-row items-center justify-evenly space-x-3 h-full text-left py-5">
        <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
          src="https://cdn.lordicon.com/hursldrn.json"
            trigger="hover"
            style="width: 150px; height: 150px"
            class="hidden lg:flex"></lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Auto-formation
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            <!-- Best software developers are often fantastic self-learners.The ideal
            skill any person can have is understanding how to learn, and ideal
            developers have acquired the skill of self-learning. -->
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
            <!-- Problem-solving is a one of the most important part of the work.
            Problem-solving also has to do with utilizing creativity and logical
            thought processes to identify problems and resolve them with
            software. -->

            Pour un développeur, la persévérance est une qualité indispensable à cultiver pour atteindre ses objectifs. Elle est cruciale et ne doit pas être négligée, car sans elle, il est impossible de concrétiser ses aspirations.
          </p>
        </div>

        <div
          class="bg-white rounded-xl drop-shadow-md mt-3 col-lg-4 ml-2 py-1 px-5 h-96 hover:-mt-3 cursor-default hover:shadow-lg hover:shadow-green-100">
          <lord-icon
          src="https://cdn.lordicon.com/mjmrmyzg.json"
          trigger="hover"
          colors="primary:#4be1ec,secondary:#cb5eee"
          class="hidden lg:flex"
          style="width:150px;height:150px">
          </lord-icon>

          <div class="text-2xl font-semibold text-green-800 mt-4 pl-1">
            Communication
          </div>
          <p class="text-left text-base lg:text-sm leading-relaxed">
            <!-- Software developers need to learn to admit their mistakes. Of
            course, making a mistake occurs to all of us. The most important
            thing to do is to make an effort to learn from them and try to avoid
            them later in life. -->

            La qualité de communication est cruciale dans le métier de développeur, 
            car elle permet de faciliter la collaboration, 
            de comprendre les besoins des clients et de transmettre efficacement les idées et les solutions techniques aux membres de l'équipe.
          </p>
        </div>
      </div>
    </div>
  </div>

  <Blog :blog="blog" />
  <Footer />
</template>

<script>
import Navbar from "./Navbar.vue";
import Header from "./Header.vue";
import Services from "./Services.vue";
import About from "./About.vue";
import Projects from "./Projects.vue";
import Contact from "./Contact.vue";
import Blog from "./Blog.vue";
import Footer from "./Footer.vue";

export default {
  name: "Home",
  data() {
    return {};
  },

  props: {
    blog: Array,
  },

  components: {
    Navbar,
    Header,
    Services,
    About,
    Projects,
    Contact,
    Blog,
    Footer,
  },
};
</script>

<style></style>
