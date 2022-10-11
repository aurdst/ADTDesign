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
              :src="require('@/assets/images/features/3/feature-img.jpg')"
              alt="feature"
              class="rounded"
            />
          </v-col>
          <v-col cols="12" md="7" lg="5" class="feature3-card">
            <v-card class="card-shadow">
              <v-card-text style="margin-top: -25px">
                <div class="pa-10 text-center">
                  <v-chip small color="info" text-color="white">
                    Pourquoi Aurélien ?
                  </v-chip>
                  <h3 class="feature3-title font-weight-medium">
                    Faite confiance à l'expertise d'Aurélien
                  </h3>
                  <p style="font-size:14px">
                    Diplomé en 2017 avec son <strong> Baccalauréat Communication Visuelle et Pluri-média (Niv 4)</strong>, en 2019 Aurélien décroche son <strong>DUT de Web Designer (niv 5)</strong>,  pour ensuite obtenir sa <strong>Bachelor de Concepteur Développeur d'application (niv 6)</strong> aujourd'hui il est fier de vous proposer son expertise dans le domaine du digital. 
                  </p>
                  <v-btn
                    color="#fff"
                    class="btn-custom-lg linking mt-10 btn-arrow"
                    nuxt
                    large
                    to="/"
                    elevation="0"
                  >
                    <a href="#projets" style="text-decoration:none; color:black"><span>Voir ses projets</span></a>
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
