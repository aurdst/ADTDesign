<template>
  <div>
    <!-- -----------------------------------------------
    Banner
    ----------------------------------------------- -->
    <Banner />
    <v-col style="z-index:999;">
      <v-row>
        <v-btn 
         color="#212E53"
         rounded
         fixed
         right
         to="/#quisommes"
        >
          <v-icon
          color="white">
            mdi-arrow-up-bold-circle
          </v-icon>
        </v-btn>
      </v-row>
    </v-col>
    <!-- -----------------------------------------------
    ./ Banner
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    All Components
    ----------------------------------------------- -->
    <AllCustomComponents />
    <!-- -----------------------------------------------
    ./ All Components
    ----------------------------------------------- -->
    <!-- -----------------------------------------------
    Coming Soon
    ----------------------------------------------- -->
    <ComingSoon />
    <!-- -----------------------------------------------
    ./ Coming Soon
    ----------------------------------------------- -->
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "ADTDesign | Web Designer | Développeur",
      meta: [
        {
          hid: "description",
          name: "DTDesign",
          content: "Créer, concevoir votre projet digital",
        },
      ],
    };
  },

  data() {
    return {};
  },
  components: {
    Banner: () => import("@/components/shared/lp-banner/Banner"),
    ComingSoon: () => import("@/components/shared/coming-soon/ComingSoon"),
    AllCustomComponents: () =>
      import("@/components/custom/AllCustomComponents"),
  },
};
</script>
