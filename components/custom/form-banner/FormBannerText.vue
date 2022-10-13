<template>
  <div>
    <div class="mini-spacer bg-extra-light">
      <v-container>
        <!-- -----------------------------------------------
            Start Form Banner Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="9" lg="7">
            <div class="text-center">
              <h2 class="ui-title font-weight-bold">Ils ont fait confiance</h2>
              <p>
                La satisfaction est au centre des préoccupations de toute entreprise
              </p>
            </div>
          </v-col>
        </v-row>

        <v-col mt-5>
          <v-row mt-5>
            <v-img
              style="margin:auto; margin-top:50px"
              :src="logo"
              max-width="400"
              mx-auto
              ></v-img>
          </v-row>
        </v-col>

        <!-- -----------------------------------------------
            End Form Banner Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "FormBannerText",
  data() {
    return {
      logo: require("@/assets/images/technologies/confiance.png")
    };
  },
  methods: {},
};
</script>
