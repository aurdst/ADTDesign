<template>
  <div>
    <div class="mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Header Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-img 
           :src="logo"
           max-width="400"
           pl-16
           ></v-img>
          <v-col cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="ui-title font-weight-bold">Qui est derrière ADTDesign ?</h2>
              
              <p>
                <strong>ADTDesign</strong> est un <strong>Web Designer</strong>, <strong>Concepteur / Développeur</strong> spécialisé dans le domaine du digital. 
                <strong>ADTDesign</strong> vous accompagne de l'idée à la conception du projet. Besoin d'une création graphique, une identitée visuelle, une présence sur le web, d'un montage vidéo, un plugin sur votre site ?
                <br><br></br>
                Alors n'hésitez pas à le contacter dès à présent !
              </p>
              <br>
              <v-btn
               class="btn_white_text"
               color="#daab39"
              >Lancer mon projet !</v-btn>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Header Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "HeaderText",
  data() {
    return {
      logo: require("@/assets/images/landingpage/webdev.png")
    };
  },
  methods: {},
};
</script>
