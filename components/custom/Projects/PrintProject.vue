<template>
    <v-row class="mt-13" v-if="showLogo">

        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/ADTDesign_featyou.jpg"
                    class="img-fluid"
                    alt="ADTDesign_featyou"
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
                    src="@/assets/images/portfolio/ADT_Design_Triomphe.png"
                    class="img-fluid"
                    alt="ADTDesign Triomphe Logo"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Triomphe Logo</h5>
                <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
            </v-card>
        </v-col>
        
        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/ADTDesign_Kangoo.png"
                    class="img-fluid"
                    alt="ADTDesign Kangoo Logo"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Kangoo Logo</h5>
                <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
            </v-card>
        </v-col>

        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/Mokup.png"
                    class="img-fluid"
                    alt="ADTDesign Golf Logo"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Golf Club Logo</h5>
                <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
            </v-card>
        </v-col>

        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/MokupArmu.png"
                    class="img-fluid"
                    alt="ADTDesign Golf Logo"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Arnold Armurerie Logo</h5>
                <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
            </v-card>
        </v-col>

        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/MokupTriceratops.png"
                    class="img-fluid"
                    alt="ADTDesign Golf Logo"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Tricératops Conception Logo</h5>
                <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
            </v-card>
        </v-col>
        
        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/ADTDesign_LightOwl.png"
                    class="img-fluid"
                    alt="ADTDesign LightOwl Logo"
                    />
                </div>
                <v-card-text>
                    <h5 class="font-weight-medium font-18">LightOwl Logo</h5>
                    <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
                </v-card>
        </v-col>

        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                    <img
                    src="@/assets/images/portfolio/MokupSecure.png"
                    class="img-fluid"
                    alt="ADTDesign LightOwl Logo"
                    />
                </div>
                <v-card-text>
                    <h5 class="font-weight-medium font-18">Secure Logo</h5>
                    <p class="font-14 mb-0">Conception de Logo</p>
                </v-card-text>
                </v-card>
        </v-col>
    </v-row>
</template>

<script>
export default{
    name: "PrintProject",
    props: ["showLogo", "toggleShowLogo"],
}
</script>