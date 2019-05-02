<template>
  <v-container fluid ma-0 pa-0 class="hero-background-circuit">
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
              <h2 class="display-1 secondary--text mt-4">CCISO Self-Paced (iLearn)</h2>
              <p class="display-1 primary--text mt-3 mb-4">$2,499</p>
              <v-container fluid grid-list-xl>
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
                    <v-btn
                      large
                      class="snipcart-add-item primary gradient mt-4"
                      data-item-id="007"
                      data-item-name="CCISO Self-Paced (iLearn)"
                      data-item-price="2499.00"
                      data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556397505/StealthEntry/eccouncil/CCISO-cover-main.jpg"
                      data-item-url="/products.json"
                      data-item-description="The CCISO Certification is an industry-leading program that recognizes the real-world experience necessary to succeed at the highest executive levels of information security. The EC-Council CCISO Body of Knowledge covers all five the CCISO Domains in depth and was written by seasoned CISOs for current and aspiring CISOs."
                    >Add to Cart</v-btn>
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