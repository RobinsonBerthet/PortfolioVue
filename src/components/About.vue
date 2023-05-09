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
              Je suis un Étudiant en développement informatique en deuxième année de BTS SIO à Angers, 
              je suis passionné par l'informatique.
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
              Je fais aussi du sport, j'aime le football et la musculation. 
              J'apprécie aussi voyager et découvrir de nouveaux pays



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
            Je suis étudiant en 2ème année de BTS SIO (Services informatiques aux Organisations) option SLAM (Solutions Logicielles et Applications Métiers),
             au lycée Chevrollier à Angers. 
            J'ai appris beaucoup de choses en développement informatique mais j'ai aussi des notions de Cybersécurité qui sont extrèmement importantes aujourd'hui.

          </p>
          <p class="mb-4">
            Grâce au BTS j'ai réalisé beaucoup de projets et j'ai eu une grande pratique dans le domaine du développement. 
            J'ai réalisé quelques applicatifs notamment en CSharp, et j'ai acquis une expérience en php durant les travaux pratiques. 
            Pour ce qui est du développement d'applications mobiles,
            je me suis familiarisé avec les bases de Flutter.
          </p>

          <p class="mb-5 hidden lg:flex">
            <!-- I also have experiences with building Nft Smart Contract and
            Blockchain Solutions as freelancer developer in South Korea. Since
            beginning my journey as a freelance developer nearly 10 months ago,
            I’ve done remote work for agencies, consulted for startups, and
            collaborated with talented people to create Nfts,Smart Contracts and
            Dapps for both business and consumer use. -->

            Durant mon BTS j'ai réalisé deux stages, cela m'a permis de découvrir le monde en entreprise, Ces expériences m'ont aidé à gagner en autonomie.
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
