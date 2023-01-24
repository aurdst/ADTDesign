<template>
    <v-row class="mt-13" v-if="showWeb">
        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
                <div class="portfolio-img">
                <a href="https://www.teamlock.io/#/" target="_blank">
                    <img
                    src="@/assets/images/portfolio/ADTDesign_Teamlock.jpg"
                    class="img-fluid"
                    alt="ADTDesign_Teamlock"
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
                    src="@/assets/images/portfolio/ADTDesign_medivie_templeuve.jpg"
                    class="img-fluid"
                    alt="ADTDesign_medivie_templeuve"
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
                    src="@/assets/images/portfolio/ADTDesign_adomeo_sport.jpg"
                    class="img-fluid"
                    alt="ADTDesign_adomeo_sport"
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
                    src="@/assets/images/portfolio/ADTDesign_Clement_huon.jpg"
                    class="img-fluid"
                    alt="ADTDesign_Clément_huon"
                />
                </a>
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Clément Huon Ostéopathe</h5>
                <p class="font-14 mb-0">Création graphique et technique du site web</p>
                </v-card-text>
            </v-card>
        </v-col>
        
    </v-row>
</template>

<script>
export default{
    name: "PrintProject",
    props: ["showWeb", "toggleShowWeb"],
}
</script>