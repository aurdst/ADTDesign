<template>
    <v-row class="mt-13" v-if="showMaquette">
        <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden" v-bind="show">
                <div class="portfolio-img">
                <img
                    src="@/assets/images/portfolio/ADTDesign_Atelier_maman.jpg"
                    class="img-fluid"
                    alt="ADTDesign_Atelier_maman"
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
                    <img
                    src="@/assets/images/portfolio/ADTDesign_arganatus.png"
                    class="img-fluid"
                    alt="ADTDesign_Arganatus_Maquette"
                />
                </div>
                <v-card-text>
                <h5 class="font-weight-medium font-18">Maquette Arganatus</h5>
                <p class="font-14 mb-0">Création Graphique</p>
                </v-card-text>
            </v-card>
        </v-col>
    </v-row>
</template>

<script>
export default{
    name: "PrintProject",
    props: ["showMaquette", "toggleShowMaquette"],
}
</script>