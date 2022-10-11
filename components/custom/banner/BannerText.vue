<template>
  <div>
    <div class="mini-spacer banner_bg" >
      <v-container class="banner_bg">
        <!-- -----------------------------------------------
            Start Banner Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="ui-title font-weight-bold" style="color:white">Technologies</h2>
              <p style="color:#f5f5f5">
                Retrouvez toutes nos technologies, outils de création : 
              </p>
              <v-col align-self="center">
                <v-row mx-auto>
                  <v-img 
                  :src="logo"
                  alt="DTDesign Technologie utilisées"
                  ></v-img>
                </v-row>
              </v-col>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Banner Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "BannerText",
  data() {
    return {
      logo: require("@/assets/images/technologies/alltech.svg")
    };
  },
  methods: {},
};
</script>
