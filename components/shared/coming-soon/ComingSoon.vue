<template>
  <div class="coming-wrapper" ref="coming-soon">
    <v-container>
      <!-- -----------------------------------------------
            Start Coming Soon
        ----------------------------------------------- -->
      <v-row id="contact">
        <v-col cols="12" sm="10" md="6" class="d-flex align-center">
          <div>
            <h2 class="coming-title font-weight-bold white--text">
              Contact par mail ou Téléphone ?<br>Tout est là !
            </h2>
            <h4 class="coming-subtitle white--text font-weight-light">
              ADTDesign disponible du Lundi au Vendredi de 9h à 18h 
            </h4>
            <div class="mt-16 pt-2">
              <v-card
                max-width="250"
                nuxt
                large
                class="btn-custom-md"
                color="white"
                elevation="0"
              >
                <strong>Aurélien : </strong> 06 15 41 18 16
              </v-card>

              <br>

              <v-card
                max-width="260"
                nuxt
                large
                class="btn-custom-md"
                color="white"
                elevation="0"
              >
                <strong>Maxime : </strong> 06 10 42 37 65
              </v-card>

              <br>
              <v-card
                max-width="600"
                nuxt
                large
                class="btn-custom-md"
                color="white"
                elevation="0"
              >
                aureliendestailleur@outlook.fr <strong>//</strong> lefebvremaximee@gmail.com
              </v-card>
            </div>
          </div>
        </v-col>
      </v-row>

      <!-- -----------------------------------------------
            End Coming Soon
        ----------------------------------------------- -->
    </v-container>
  </div>
</template>
<script>
export default {
  name: "ComingSoon",
  data() {
    return {};
  },
  methods: {}
};
</script>
