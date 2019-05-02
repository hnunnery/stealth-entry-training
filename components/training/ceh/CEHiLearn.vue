<template>
  <v-container fluid ma-0 pa-0 class="hero-background-circuit">
    <v-layout row wrap justify-center align-center>
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
                alt="CEH"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text mt-4">CEH Self-Paced (iLearn)</h2>
              <p class="display-1 primary--text mt-3 mb-4">$1,899</p>
              <v-container fluid>
                <v-layout wrap justify-center align-center>
                  <v-flex xs12 sm10>
                    <p class="title secondary--text text-xs-left">Base Package Includes:</p>
                    <ul class="subheading secondary--text text-xs-left">
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Streaming Video Training Modules – 1 year access
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Official EC-Council e-courseware – 1 year access
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; iLabs, Virtual Lab Platform – 6 months access
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Instructor-led Training Modules
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Certificate of Completion
                      </li>
                    </ul>
                    <v-layout row wrap justify-center>
                      <v-flex xs12 sm6 pa-0 v-show="!courseHome">
                        <v-btn to="/courses/ceh" large class="secondary mt-4">CEH Info</v-btn>
                      </v-flex>
                      <v-flex xs12 sm6>
                        <v-btn
                          to="/courses/ceh/ilearn"
                          large
                          class="primary gradient mt-4"
                        >Purchase Course</v-btn>
                      </v-flex>
                    </v-layout>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  props: ["courseHome"]
};
</script>
