<template>
  <v-container fluid ma-0 pa-0 class="hero-background-circuit">
    <v-layout row wrap justify-center align-center>
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/ECSAV10-Cover.jpg"
                alt="ECSA"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text mt-4">ECSA Live Online (iWeek)</h2>
              <p class="display-1 primary--text mt-3 mb-0">$2,999</p>
              <v-container fluid grid-list-xl>
                <v-layout wrap justify-center align-center>
                  <v-flex xs12 sm10>
                    <v-select :items="dates" label="Choose Dates" v-model="courseDate"></v-select>
                    <p class="title secondary--text text-xs-left mt-2">Base Package Includes:</p>
                    <ul class="subheading secondary--text text-xs-left">
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Live online instructor-led
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Official Printed Courseware
                      </li>
                      <li>
                        <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; iLabs (6 Months Access)
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
                      data-item-id="014"
                      data-item-name="ECSA Live Online (iWeek)"
                      data-item-price="2999.00"
                      data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/ECSAV10-Cover.jpg"
                      data-item-url="/products.json"
                      data-item-custom1-name="Dates"
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
        "Oct 6-9, 2019"
      ]
    };
  }
};
</script>