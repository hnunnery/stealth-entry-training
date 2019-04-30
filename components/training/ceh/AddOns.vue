<template>
  <v-container fluid ma-0 pa-0>
    <v-layout row wrap justify-center>
      <v-flex xs12 lg10 xl8 class="py-4 px-2 orange elevation-12">
        <h2 class="display-2 white--text text-xs-center my-title">Optional Add On Items</h2>
      </v-flex>
      <!-- STORM Took Kit -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480414/StealthEntry/eccouncil/storm-toolkit-product-3.jpg"
                alt="STORM"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">STORM - Mobile Security Tool Kit</h2>
              <p class="display-1 primary--text mt-3 mb-4">$499</p>
              <p>(Sold AS-IS with no warranties expressed or implied)</p>
              <p class="title">Includes free t-shirt and sticker!</p>
              <p
                class="subheading text-xs-left"
              >EC-Council’s Mobile Security Toolkit (Better known as the STORM!) is a fully-loaded pen-test platform which comes equipped with STORM Linux (a Raspbian based, customized distro of Linux equipped with the industry’s most popular hacking tools) loaded onto a portable touchscreen device.</p>
              <p class="subheading text-xs-left">Regular Price: $749</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="101"
                data-item-name="STORM - Mobile Security Tool Kit"
                data-item-price="499.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480414/StealthEntry/eccouncil/storm-toolkit-product-3.jpg"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- Gale Force 10 Expansion Pack -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480412/StealthEntry/eccouncil/Storm-accessories.png"
                alt="Gale Force"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">Gale Force 10 Expansion Pack</h2>
              <p class="display-1 primary--text mt-3 mb-4">$427</p>
              <p
                class="subheading text-xs-left"
              >Turn your STORM into a hurricane with the Gale Force 10 expansion pack! EC-Council has assembled the ultimate set of accessories to make your STORM Mobile Security Toolkit even more powerful.</p>
              <p
                class="subheading text-xs-left"
              >This expansion pack adds independent power for complete mobility, further reach, Wi-Fi and radio tools for packet sniffing, drone detection, as well as the ability to add devices to complete your hacking network and isolate it from the customer network both on Wi-Fi and physical Ethernet.</p>
              <p
                class="text-xs-left"
              >*The Gale Force 10 Expansion Pack is sold as a bundle and not as individual components.</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="102"
                data-item-name="Gale Force 10 Expansion Pack"
                data-item-price="427.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480412/StealthEntry/eccouncil/Storm-accessories.png"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- CEH tshirt -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480400/StealthEntry/eccouncil/CEH-tshirt-3.jpg"
                alt="tshirt"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">CEH T-Shirt</h2>
              <p class="display-1 primary--text mt-3 mb-4">$25</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="103"
                data-item-name="CEH T-Shirt"
                data-item-price="25.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480400/StealthEntry/eccouncil/CEH-tshirt-3.jpg"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
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
      storm: false,
      expansion: false,
      tshirt: false
    };
  }
};
</script>

<style lang="scss" scoped>
@media screen and (max-width: 599px) {
  .my-title {
    font-size: 2.5em !important;
  }
}
</style>
