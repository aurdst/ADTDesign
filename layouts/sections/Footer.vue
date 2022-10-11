<template>
  <!-- -----------------------------------------------
        Start Footer
  ----------------------------------------------- -->
  <v-footer class="footer">
    <v-container>
      <v-row class="py-0 py-md-15">
        <!-- -----------------------------------------------
        First Column
      ----------------------------------------------- -->
        <v-col cols="12" sm="12" md="12" lg="3" class="px-xs-0">
          <h4 class="font-weight-regular font-18">Addresse</h4>
          <p class="mt-10">27 Avenue Robert Schuman, Mons en Baroeul</p>
        </v-col>
        <!-- -----------------------------------------------
        Second Column
      ----------------------------------------------- -->
        <v-col cols="12" sm="12" md="12" lg="3" class="px-xs-0">
          <h4 class="font-weight-regular font-18">Téléphone</h4>
          <p class="mt-10 mb-0">Aurélien : +336 15 41 18 16</p>
        </v-col>
        <!-- -----------------------------------------------
        Third Column
      ----------------------------------------------- -->
        <v-col cols="12" sm="12" md="12" lg="3" class="px-xs-0">
          <h4 class="font-weight-regular font-18">Email</h4>
          <p class="mt-10 mb-0">
            Office : <a class="dark-link" href="/">info@wrappixel.com</a>
          </p>

        </v-col>
        <!-- -----------------------------------------------
        Fourth Column
      ----------------------------------------------- -->
        <v-col cols="12" sm="12" md="12" lg="3" class="px-xs-0">
          <h4 class="font-weight-regular font-18">Social</h4>

          <div class="social-icons mt-10">
            <a href="https://github.com/aurdst">
              <i class="mdi mdi-github"></i>
            </a>
            <a href="#">
              <i class="mdi mdi-linkedin"></i>
            </a>

            <a href="#">
              <i class="mdi mdi-instagram"></i>
            </a>
          </div>
        </v-col>
      </v-row>
      <div class="footer-bottom-bar font-14">
        <div class="d-block d-md-flex align-center">
          <p>
            All Rights Reserved by
            <a href="https://www.wrappixel.com/" class="link">wrappixel.com</a>
          </p>
          <div class="ml-auto">
            <div class="d-flex align-center">
              <a href="/" class="link px-4">Terms of Use</a>
              <a href="/" class="link px-4">Legal Disclaimer</a>
              <a href="/" class="link px-4">Privacy Policy</a>
            </div>
          </div>
        </div>
      </div>
    </v-container>
  </v-footer>
  <!-- -----------------------------------------------
        End Footer
  ----------------------------------------------- -->
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      data: [],
    };
  },
  components: {},
};
</script>
 