<template>
  <v-container>
    <v-layout row wrap justify-center align-center my-5>
      <v-flex xs10 sm8 md6 lg4 class="padding">
        <v-img
          src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
          alt="CEH"
          class="responsive-img elevation-12"
        ></v-img>
      </v-flex>
      <v-flex xs12 sm10 md6 lg6 class="text-xs-center padding">
        <h2 class="display-1 secondary--text mt-4">CEH Live In Person</h2>
        <p class="display-1 primary--text mt-3 mb-4">$2,899</p>
        <p class="title primary--text">Choose Dates in Cart</p>
        <p class="title secondary--text text-xs-left">Base Package Includes:</p>
        <ul class="subheading secondary--text text-xs-left">
          <li>
            <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Instructor-led In Person Training
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
          class="snipcart-add-item primary gradient mt-4"
          data-item-id="003"
          data-item-name="CEH Live In Person"
          data-item-price="2899.00"
          data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
          data-item-url="/products.json"
          data-item-custom1-name="Choose Course"
          data-item-custom1-required="true"
          data-item-custom1-options="25May - 30May 2019 - Tampa, FL| 5June - 10June 2019 - Las Vegas, NV | 15July - 20July 2019 - San Francisco, CA"
        >Add to Cart</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style lang="scss" scoped>
@media screen and (min-width: 600px) {
  .padding {
    padding-left: 50px !important;
    padding-right: 50px !important;
  }
}
</style>