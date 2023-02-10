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
                Consulter les projets ADSTDesign
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
            Button Portfolio
        ----------------------------------------------- -->
        <v-row align="center" justify="center">
          <v-col cols="2">
            <v-btn color="#212E53" small outlined rounded v-on:click="toggleShowMaquette">
              Maquettes
            </v-btn>
          </v-col>

          <v-col cols="2">
            <v-btn color="#212E53" outlined small rounded v-on:click="toggleShowLogo">
              Logos / Print
            </v-btn>
          </v-col>

          <v-col cols="2">
            <v-btn color="#212E53" outlined small rounded v-on:click="toggleShowWeb">
              Sites Web / App Mobile
            </v-btn>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            Start Portfolio
        ----------------------------------------------- -->
          <PrintProject v-bind:showLogo="showLogo" v-bind:toggleShowLogo="toggleShowLogo"/>
          <WebProject v-bind:showWeb="showWeb" v-bind:toggleShowWeb="toggleShowWeb"/>
          <MaquetteProject v-bind:showMaquette="showMaquette" v-bind:toggleShowMaquette="toggleShowMaquette"/>
          <br>
          <!-- -----------------------------------------------
            End Portfolio
            ----------------------------------------------- -->
          <div style="padding: 30px; border-radius: 30px; background: linear-gradient(90deg, #137C8B 0%, #709CA7 100%);">
            <br>
              <h2 style="text-align: center; color: white;">Notre Équipe : </h2>
            <br>
            <br>
            <br>
          <v-row>
            <v-col
            cols="6"
            mx-auto>
            <div style="text-align:center">
              <v-avatar
              size="62"
              >
                  <img
                      src="@/assets/images/team/ADTDesign_LEFEBVRE_Maxime.PNG"
                      alt="Maxime_Lefebvre"
                      mx-auto
                  >
              </v-avatar>
            </div>
              <br>
              <h3 style="text-align:center; color: white;font-weight: 900;">Maxime LEFEBVRE</h3>
              <div style="background:white; height:1px; width:70px; margin:auto;"></div>
              <br>
              <h4 style="text-align:center; color: white; font-weight: 600;">Concepteur - Développeur d'Application Web & Mobile</h4>
              <h5 style="text-align:center; color: white; font-weight: 100;">Création API REST Symfony, Fast API, Phalcon, Wordpress, OCR, Création de graphique technique & Pannel Administration</h5>
            </v-col>
  
            <v-col
            cols="6"
            mx-auto>
            <div style="text-align:center">
              <v-avatar
              size="62"
              >
                  <img
                      src="@/assets/images/team/ADTDesign_DESTAILLEUR_Aurelien.png"
                      alt="John"
                      mx-auto
                  >
              </v-avatar>
            </div>
              <br>
              <h3 style="text-align:center; color: white;font-weight: 900;">Aurélien DESTAILLEUR</h3>
              <div style="background:white; height:1px; width:70px; margin:auto;"></div>
              <br>
              <h4 style="text-align:center; color: white; font-weight: 600;">WebDesigner - Développeur d'Application Web & Mobile</h4>
              <h5 style="text-align:center; color: white; font-weight: 100;">Création API REST Fast API, VueJS / Vuetify, Wordpress, Création graphique & communication visuelle, Montage Vidéo</h5>
            </v-col>
  
          </v-row>
        </div>


      </v-container>
    </div>
  </div>
</template>
<script>
import PrintProject from "../Projects/PrintProject.vue"
import WebProject from "../Projects/WebProject.vue"
import MaquetteProject from "../Projects/MaquetteProject.vue"

export default {
  name: "Portfolio",
  data() {
    return {
      showLogo: false,
      showMaquette: true,
      showWeb: false,
    };
  },
  components:{
    PrintProject,
    WebProject,
    MaquetteProject,
  }, 
  methods: {
    toggleShowLogo: function(){
      this.showLogo = !this.showLogo
      this.showWeb = false
      this.showMaquette = false
    },

    toggleShowWeb: function(){
      this.showWeb = !this.showWeb
      this.showMaquette = false
      this.showLogo = false
    },

    toggleShowMaquette: function(){
      this.showMaquette = !this.showMaquette
      this.showLogo = false
      this.showWeb = false
    }
  },
};
</script>
