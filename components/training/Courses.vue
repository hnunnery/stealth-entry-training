<template>
  <v-container fluid class="pb-5 orange hero-background-circuit">
    <v-layout row wrap justify-center align-center class="pa-0 ma-0">
      <v-flex xs12 xl10>
        <h2 class="display-1 secondary--text text-xs-center my-3">Choose a Course</h2>
        <v-layout row wrap justify-center>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/ceh">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
                alt="CEH"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/cnd">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CND-cover-main.jpg"
                alt="CND"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/cciso">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/v1556397505/StealthEntry/eccouncil/CCISO-cover-main.jpg"
                alt="CCISO"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <!-- <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/chfi">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397355/StealthEntry/eccouncil/CHFI-cover-main.jpg"
                alt="CHFI"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/certified-security-analyst">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/ECSAV10-Cover.jpg"
                alt="ECSA"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/certified-security-analyst">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397512/StealthEntry/eccouncil/CSCU-cover-main.jpg"
                alt="CSCU"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/certified-security-analyst">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397749/StealthEntry/eccouncil/EDRP-featured.jpg"
                alt="EDRP"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>
          <v-flex xs12 sm6 md3 xl2 class="text-xs-center pa-3">
            <nuxt-link to="/courses/certified-security-analyst">
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397883/StealthEntry/eccouncil/ECIH-Product-Cover.jpg"
                alt="ECIH"
                class="responsive-img elevation-12 course-tile"
              ></v-img>
            </nuxt-link>
          </v-flex>-->
        </v-layout>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style lang="scss" scoped>
.course-tile:hover {
  outline: 1px solid #ffffff;
}
</style>


