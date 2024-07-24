<template>
  <div class="bg-green-50 page-section pt-5 -mb-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center hidden lg:flex">
            <lottie-player
              src="https://assets2.lottiefiles.com/packages/lf20_qhrndegx.json"
              background="transparent"
              speed="1"
              style="max-width: 500px; max-height: 500px"
              autoplay></lottie-player>
          </div>
        </div>

        <div class="col-lg-6 p-4">
          <h2 class="title-section text-2xl">
            A propos
            <span class="marked">De Moi</span>
          </h2>
          <div class="divider"></div>

          <div>
            <p>
              Je suis un Étudiant en développement informatique en Licence Professionnelle | Métiers de l’informatique : applications web à la faculté des Sciences d'Angers. 
              Depuis la classe de première et grâce à la spécialité NSI (Numérique et Science Informatique) je me suis petit à petit intéressé à l'informatique et plus particulièrement au développement, cette passion s'est ensuite développée durant l'enseignement supérieur pendant mon BTS SIO jusqu'à cette année.
            </p>
          </div>

          <div>
            <p>
              <!-- I'm a well organized person, problem solver, independent employee
              with high attention to detail. Fan of Football and Boxing, outdoor
              activities with my friends, TV series and English literature.
              Actually, I have been living in South Korea for 5 years, I So i'm
              also good in Korean. -->

              Je suis assez curieux dans mon travail et je persévère sur les problèmes que je rencontre. 
              Mes passe temps sont le sport notamment la musculation et la course à pieds. 
              J'apprécie aussi voyager et découvrir de nouveaux pays.



            </p>
          </div>

          <div>
            <p class="hidden lg:flex">
              <!-- And I'm interested in the entire creative frontend spectrum and
              working on ambitious projects with positive people. -->
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
  <!-- .page-section -->

  <div class="bg-green-50 page-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 p-4 -mt-9 lg:mt-0">
          <h2 class="title-section text-2xl">
            Mes
            <span class="marked">Compétences & Expériences</span>
          </h2>
          <div class="divider"></div>
          <p class="mb-4">

            Depuis la classe de première j'ai pu développer des compétences en informatique en ciblant plus le développement web, logiciel et applicatif avec le BTS SIO option SLAM (Solutions Logicielles et Applications Métiers), j'ai aussi acquis des notions importantes en réseau.

          </p>
          <p class="mb-4">
            Grâce au BTS et à la licence professionnelle j'ai réalisé beaucoup de projets et j'ai eu une bonne pratique dans le domaine du développement web. 
            J'ai aussi réalisé quelques applicatifs notamment en CSharp.
            
          </p>

          <p class="mb-4">
            Le BTS SIO et la licence professionnelle m'ont permis d'acquérir une expérience en entreprise grâce aux stages réalisés en première et deuxième année de BTS. De plus, 
            je suis actuellement en licence professionnelle en alternance, ce qui m'apporte beaucoup, 
            tant au niveau du développement de mon autonomie, de l'apprentissage des langages de programmation, 
            que des compétences relationnelles acquises lors des réunions.
            
          </p>

          <p class="mb-5 hidden lg:flex">
            <!-- I also have experiences with building Nft Smart Contract and
            Blockchain Solutions as freelancer developer in South Korea. Since
            beginning my journey as a freelance developer nearly 10 months ago,
            I’ve done remote work for agencies, consulted for startups, and
            collaborated with talented people to create Nfts,Smart Contracts and
            Dapps for both business and consumer use. -->

            <!-- Durant mon BTS j'ai réalisé deux stages, cela m'a permis de découvrir le monde en entreprise, Ces expériences m'ont aidé à gagner en autonomie. -->
          </p>

          <router-link to="/projets" class="btn btn-primary">
            Mes Projets
          </router-link>
        </div>
        <div class="col-lg-6 py-3 wow zoomIn">
          <div class="img-place text-center">
            <lottie-player
              src="https://assets2.lottiefiles.com/packages/lf20_u4jjb9bd.json"
              background="transparent"
              speed="0.5"
              style="max-width: 550px; max-height: 550px"
              loop
              autoplay></lottie-player>
          </div>
        </div>
      </div>
    </div>
    <!-- .container -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      scrollPosition: 0,
    };
  },

  methods: {
    handleScroll(e) {
      this.scrollPosition = e.target.scrollTop;

      if (this.scrollPosition > 100) {
        console.log("UP");
      } else {
        console.log("DOWN");
      }
    },
  },
};
</script>

<style></style>
