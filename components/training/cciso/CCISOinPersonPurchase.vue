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
              <h2 class="display-1 secondary--text mt-4">CCISO Live In Person</h2>
              <p class="display-1 primary--text mt-3 mb-0">$3,499</p>
              <v-container fluid grid-list-xl>
                <v-layout wrap justify-center align-center>
                  <v-flex xs12 sm10>
                    <v-select :items="dates" label="Choose Dates" v-model="courseDate"></v-select>
                    <p class="title secondary--text text-xs-left">Base Package Includes:</p>
                    <ul class="subheading secondary--text text-xs-left">
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Instructor-led In Person Training
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
                    <v-btn
                      large
                      :disabled="!courseDate"
                      class="snipcart-add-item primary gradient mt-4"
                      data-item-id="008"
                      data-item-name="CCISO Live In Person"
                      data-item-price="3499.00"
                      data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397505/StealthEntry/eccouncil/CCISO-cover-main.jpg"
                      data-item-url="/products.json"
                      data-item-custom1-name="Course"
                      data-item-custom1-required="true"
                      :data-item-custom1-value="this.courseDate"
                    >Add to Cart</v-btn>
                    <p v-if="!courseDate" class="primary--text">Please Choose Dates</p>
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
  data() {
    return {
      courseDate: "",
      dates: [
        "Denver, CO | May 6-10, 2019",
        "Las Vegas, NV | June 24-28, 2019",
        "Austin, TX | June 10-14, 2019",
        "Dallas, TX | July 15-19, 2019",
        "Niagara Falls, Canada | Aug 18-22, 2019",
        "Albuquerque, NM | Aug 19-23, 2019",
        "Atlanta, GA | Oct 6-9, 2019 (Hacker Halted)",
        "Washington, DC | Nov 11-15, 2019",
        "Tampa, FL | Dec 9-13, 2019 (Hacker Halted)"
      ]
    };
  }
};
</script>