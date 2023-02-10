<template>
  <div>
    <div class="banner1-component">
      <v-container>
        <!-- -----------------------------------------------
            Start Banner1
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" md="7" lg="6" class="d-flex align-center">
            <div class="text-center text-md-left">
              <v-chip small class="bg-dark" text-color="white">
                Information pratique
              </v-chip>
              <h2
                class="
                  banner1-title
                  font-weight-bold
                  text-uppercase
                  darkgrey--text
                "
              >
                4,95 Millards d'utilisateurs sur internet en 2022
              </h2>
              <p class="black--text op-8 font-weight-regular">
                D'après le rapport annuel réalisé par le Blog du Moderateur et Hootsuite, 192 millions de nouveaux internautes 
                dans le monde ont utilisé internet entre janvier 2020 et janvier 2021. Nous comptons alors 4,95 milliards
                 d'utilisateurs d'internet dans le monde entier en 2022. En France, le nombre d’utilisateurs d’internet monte à 60,92 millions en 2022, 
                 soit environ 93% de la population française.
              </p>
              <div class="mt-16 pt-2">
                <v-btn
                  nuxt
                  large
                  rounded
                  class="btn-custom-md"
                  depressed
                >
                  <a href="https://www.sitew.com/Informations-diverses-sur-la-creation-de-site/statistiques-web" target="_blank" style="text-decoration:none; color:black;">En savoir plus</a>
                </v-btn>
              </div>
            </div>
          </v-col>
          <v-col cols="12" md="5" lg="5">
            <v-img
              :src="require('@/assets/images/banner/banner1.png')"
              alt="banner"
            />
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Banner1
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Banner1",
  data() {
    return {};
  },
  methods: {}
};
</script>
