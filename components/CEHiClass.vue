<template>
  <v-container>
    <v-layout row wrap justify-center align-center my-5>
      <v-flex xs10 sm8 md6 xl4 class="padding">
        <v-img
          src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
          alt="CEH"
          class="responsive-img elevation-12"
        ></v-img>
      </v-flex>
      <v-flex xs12 sm10 md6 class="text-xs-center padding">
        <h2 class="display-1 secondary--text mt-4">CEH Self-Paced (iClass)</h2>
        <p class="display-1 primary--text mt-3 mb-4">$1,899</p>
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
        <v-btn
          large
          class="snipcart-add-item primary gradient mt-4"
          data-item-id="001"
          data-item-name="CEH Self-Paced (iClass)"
          data-item-price="1899.00"
          data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134832/StealthEntry/eccouncil/CEH-Cover-v10-2.jpg"
          data-item-url="/products.json"
          data-item-description="The worlds most advanced ethical hacking course with 20 of the most current security domains an ethical hacker will want to know when planning to beef up the information security posture of their organization."
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