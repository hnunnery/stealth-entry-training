<template>
  <v-container fluid ma-0 pa-0>
    <v-layout row wrap justify-center align-center>
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397505/StealthEntry/eccouncil/CCISO-cover-main.jpg"
                alt="CCISO"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text mt-4">CCISO Live Online (iWeek)</h2>
              <p class="display-1 primary--text mt-3 mb-0">$3,499</p>
              <v-container fluid grid-list-xl>
                <v-layout wrap justify-center align-center>
                  <v-flex xs12 sm10>
                    <h5 class="title secondary--text text-xs-left mb-3">Scheduled Courses:</h5>
                    <ul class="subheading secondary--text text-xs-left">
                      <li v-for="(date, index) in dates" :key="index">{{date}}</li>
                    </ul>
                    <p class="title secondary--text text-xs-left mt-3">Base Package Includes:</p>
                    <ul class="subheading secondary--text text-xs-left">
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; iWeek – Live online instructor-led
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Official Printed Courseware
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Certificate of Completion
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Exam Preparation
                      </li>
                    </ul>
                    <v-layout row wrap justify-center>
                      <v-flex xs12 sm6 pa-0 v-show="!courseHome">
                        <v-btn to="/courses/cciso" large class="secondary mt-4">CCISO Info</v-btn>
                      </v-flex>
                      <v-flex xs12 sm6 pa-0>
                        <v-btn
                          to="/courses/cciso/iweek"
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
  props: ["courseHome"],
  data() {
    return {
      courseDate: "",
      dates: [
        "May 6-10, 2019",
        "June 10-14, 2019",
        "July 15-19, 2019",
        "Aug 19-23, 2019",
        "Oct 6-9, 2019",
        "Dec 9-13, 2019"
      ]
    };
  }
};
</script>