<template>
  <div class="banner-wrapper">
    <v-container>
      <!-- -----------------------------------------------
            Start Banner
        ----------------------------------------------- -->
      <v-row justify="center">
        <v-col cols="12" md="7" lg="6" class="d-flex align-center">
          <div class="text-center text-md-left">
            <h1 class="banner-title font-weight-bold white--text">
                Designer, Developper, <br> For you.
            </h1>
            <h4 class="banner-subtitle white--text font-weight-regular">
              Développer vos projets digitaux en tout sérénité.
            </h4>
            <div class="mt-16 pt-2">
              <v-btn
                color="#DAAB3A"
                class="mr-0 mr-md-8 mb-5 mb-md-0 btn-custom-md"
                nuxt
                large
                target="_blank"
                href="/"
                elevation="0"
              >
                Découvrir nos offres digitales
              </v-btn>
              <v-btn
                nuxt
                large
                to="/coming-soon"
                class="btn-custom-md"
                outlined
                color="white"
                elevation="0"
              >
                En savoir plus
              </v-btn>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="5" lg="6">
          <v-img
            :src="require('@/assets/images/landingpage/App_Integration.png')"
            alt="banner"
          />
        </v-col>
      </v-row>

      <!-- -----------------------------------------------
            End Banner
        ----------------------------------------------- -->
    </v-container>
  </div>
</template>
<script>
export default {
  name: "Banner",
  data() {
    return {};
  }
};
</script>
