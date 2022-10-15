<template>
  <div>
    <div class="portfolio-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Portfolio Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col id="projets" cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="section-title font-weight-medium">
                Les projets d'Aurélien
              </h2>
              <p>
                Découvrez toutes ses réalisations :
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Portfolio Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Portfolio
        ----------------------------------------------- -->
        <v-row class="mt-13">
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <img
                  src="@/assets/images/portfolio/img1.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Maquette l'Atelier de maman
                </h5>
                <p class="font-14 mb-0">Graphisme</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <a href="https://www.teamlock.io/#/" target="_blank">
                  <img
                  src="@/assets/images/portfolio/img2.jpg"
                  class="img-fluid"
                  alt="portfolio"
                />
                </a>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Teamlock</h5>
                <p class="font-14 mb-0">Conception graphique & Création du site web</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <a href="https://www.medivie-templeuve.fr/" target="_blank">
                  <img
                  src="@/assets/images/portfolio/img3.jpg"
                  class="img-fluid"
                  alt="medivie_templeuve_ADTDesign"
                />
                </a>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Médivie Templeuve</h5>
                <p class="font-14 mb-0">Création du site web</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <a href="https://www.adomeo-sport.com/" target="_blank">
                  <img
                  src="@/assets/images/portfolio/img4.jpg"
                  class="img-fluid"
                  alt="adomeo_sport_ADTDesign"
                />
                </a>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">ADOMEO Sport</h5>
                <p class="font-14 mb-0">Création du site web</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                <a href="https://www.huon-osteopathe.fr/" target="_blank">
                  <img
                  src="@/assets/images/portfolio/img6.jpg"
                  class="img-fluid"
                  alt="medivie_templeuve_ADTDesign"
                />
                </a>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Clément Huon Ostéopathe</h5>
                <p class="font-14 mb-0">Création graphique et technique du site web</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                  <img
                  src="@/assets/images/portfolio/img5.jpg"
                  class="img-fluid"
                  alt="Featyou_ADTDesign"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">FeatYou Fit Better</h5>
                <p class="font-14 mb-0">Création graphique</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                  <img
                  src="@/assets/images/portfolio/img6.jpg"
                  class="img-fluid"
                  alt="Featyou_ADTDesign"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Clément Huon</h5>
                <p class="font-14 mb-0">Création Site web</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img">
                  <img
                  src="@/assets/images/portfolio/img7.jpg"
                  class="img-fluid"
                  alt="Featyou_ADTDesign"
                />
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">Maquette Arganatus</h5>
                <p class="font-14 mb-0">Création Graphique</p>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Portfolio
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Portfolio",
  data() {
    return {};
  },
  methods: {},
};
</script>
