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
