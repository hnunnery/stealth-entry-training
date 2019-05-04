<template>
  <v-container fluid ma-0 pa-0 class="hero-background-circuit">
    <v-layout row wrap justify-center>
      <v-flex xs12 lg10 xl8 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-up"
          data-aos-delay="100"
          data-aos-offset="0"
          data-aos-duration="1000"
        >Optional Add On Items</h2>
      </v-flex>

      <!-- EDRP Textbook -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556997692/StealthEntry/eccouncil/EDRP-book.png"
                alt="textbook"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">EDRP Textbook</h2>
              <p class="display-1 primary--text mt-3 mb-4">$250</p>
              <p class="text-xs-center">*Note: Ships to US, Canada and Australia ONLY!</p>
              <p class="subheading text-xs-center">
                Regular Price: $877
                <span class="primary--text">(Only $250 when buying the course)</span>
              </p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="121"
                data-item-name="EDRP Textbook"
                data-item-price="250.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556997692/StealthEntry/eccouncil/EDRP-book.png"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- Academic Credits -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480407/StealthEntry/eccouncil/academic-credits-addon-1.jpg"
                alt="credits"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">Academic Credits</h2>
              <p class="display-1 primary--text mt-3 mb-4">$260</p>
              <p
                class="title text-xs-center"
              >Turn Certification into Education with Academic Credits!</p>
              <p
                class="subheading text-xs-left"
              >An articulation agreement between EC-Council and EC-Council University allows students to attain non-degree course credits by attending EC-Council certification courses and passing their associated exam!</p>
              <p class="title text-xs-left">Fee Breakdown:</p>
              <p class="subheading text-xs-left">Application Fee - $100.00</p>
              <p class="subheading text-xs-left">Per Credit Hour $50.00 (x3)</p>
              <p class="subheading text-xs-left">Official Transcript - $10.00</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="104"
                data-item-name="Academic Credits"
                data-item-price="260.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480407/StealthEntry/eccouncil/academic-credits-addon-1.jpg"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- iLabs additional six months -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480398/StealthEntry/eccouncil/ilabs-addon-324x324.jpg"
                alt="ilabs"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">iLabs Additional 6 months</h2>
              <p class="display-1 primary--text mt-3 mb-4">$199</p>
              <p
                class="subheading text-xs-left"
              >6 months access to EC-Council's official Online lab environment (iLabs) with all tools pre-loaded into platform.</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="107"
                data-item-name="iLabs Additional 6 months"
                data-item-price="199.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480398/StealthEntry/eccouncil/ilabs-addon-324x324.jpg"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style lang="scss" scoped>
@media screen and (max-width: 599px) {
  .my-title {
    font-size: 2.5em !important;
  }
}
</style>
