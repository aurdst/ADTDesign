<template>
  <div>
    <div class="feature3-component mini-spacer">
      <v-container class="position-relative">
        <!-- -----------------------------------------------
            Start Feature 3 Text
        ----------------------------------------------- -->
        <v-row>
          <v-col cols="12" lg="10">
            <v-img
              :src="require('@/assets/images/features/3/feature-img.png')"
              alt="feature"
              class="rounded"
            />
          </v-col>
          <v-col cols="12" md="7" lg="5" class="feature3-card">
            <v-card class="card-shadow">
              <v-card-text style="margin-top: -25px">
                <div class="pa-10 text-center">
                  <v-chip small color="#212E53" text-color="white">
                    Pourquoi ADTDesign  ?
                  </v-chip>
                  <h3 class="feature3-title font-weight-medium">
                    Faite confiance à l'expertise d'Aurélien & de Maxime
                  </h3>
                  <p style="font-size:14px">
                    <br>
                    <strong style="color:black">Aurélien : </strong>Diplomé en 2017 avec son <strong> Baccalauréat Communication Visuelle et Pluri-média (Niv 4)</strong>, en 2019 Aurélien décroche son <strong>DUT de Web Designer (niv 5)</strong>,  pour ensuite obtenir sa <strong>Bachelor de Concepteur Développeur d'application (niv 6)</strong> aujourd'hui il est fier de vous proposer son expertise dans le domaine du digital. 
                    <br><br>
                    <strong style="color:black">Maxime : </strong>Diplomé d'un  <strong>DUT</strong> en 2021 <strong> (Développeur Web & Mobile (Niv 5))</strong>, il obtient ensuite 2022 sa <strong>Licence de Développeur fullStack (niv 6)</strong></p> Force de proposition <strong>Maxime</strong> est à l'écoute pour tous vos projets digitaux
                  <v-btn
                    color="#fff"
                    class="btn-custom-lg linking mt-10 btn-arrow"
                    nuxt
                    large
                    to="/#projets"
                    elevation="0"
                  >
                    <span>Voir nos projets</span>
                    <i class="mdi mdi-arrow-right"></i>
                  </v-btn>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 3 Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Feature3",
  data() {
    return {};
  },
  methods: {},
};
</script>
