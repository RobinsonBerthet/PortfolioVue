<template>
  <div class="justify-content-center">
    <section class="page_404">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <div class="col-sm-10 col-sm-offset-1 text-center">


              <div class="contant_box_404">
                <h3 class="h2">Cette Page n'est pas disponible  </h3>


                <router-link to="/" class="link_404">Revenir à l'accueil</router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
.page_404 {
  margin-top: 50px;
  padding: 40px 0;
  background: #fff;
  font-family: "Arvo", serif;
  margin-left: auto;
  margin-right: auto;
}

.page_404 img {
  width: 100%;
}

.four_zero_four_bg {
  background-color: rgba(110, 255, 220, 0.1);
  height: 400px;
  background-position: center;
}

.four_zero_four_bg h1 {
  font-size: 80px;
}

.four_zero_four_bg h3 {
  font-size: 80px;
}

.link_404 {
  color: #fff !important;
  padding: 10px 20px;
  background: #39ac31;
  margin: 20px 0;
  display: inline-block;
}
.contant_box_404 {
  margin-top: -50px;
}
</style>
