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
              <p class="title">Includes free t-shirt and sticker!</p>
              <p
                class="subheading text-xs-left"
              >EC-Council’s Mobile Security Toolkit (Better known as the STORM!) is a fully-loaded pen-test platform which comes equipped with STORM Linux (a Raspbian based, customized distro of Linux equipped with the industry’s most popular hacking tools) loaded onto a portable touchscreen device.</p>
              <ul class="subheading secondary--text text-xs-left mb-3">
                <li>
                  <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Keyboard
                </li>
                <li>
                  <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Carry Case
                </li>
                <li>
                  <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; STORM T-shirt
                </li>
                <li>
                  <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; STORM Sticker
                </li>
                <li>
                  <v-icon small class="green--text">fas fa-check-circle</v-icon>&nbsp; Access to the STORM Resource Center (Video Demos, Support, ISO Image Download)
                </li>
              </ul>
              <p class="text-xs-left">*Sold AS-IS with no warranties expressed or implied</p>
              <p class="subheading text-xs-left">
                Regular Price: $749
                <span class="primary--text">(Only $499 when buying the course)</span>
              </p>
              <v-layout row wrap justify-center align-center>
                <v-flex xs12 sm6 pa-0>
                  <v-btn to="/storm" large class="secondary mt-2 mb-4">More Info</v-btn>
                </v-flex>
                <v-flex xs12 sm6 pa-0>
                  <v-btn
                    large
                    class="snipcart-add-item primary gradient mt-2 mb-4"
                    data-item-id="101"
                    data-item-name="STORM - Mobile Security Tool Kit"
                    data-item-price="499.00"
                    data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480414/StealthEntry/eccouncil/storm-toolkit-product-3.jpg"
                    data-item-url="/products.json"
                    data-item-custom1-name="Shirt Size"
                    data-item-custom1-required="true"
                    data-item-custom1-value="LG"
                    data-item-custom1-options="SM|MD|LG|XL"
                  >Add to Cart</v-btn>
                </v-flex>
              </v-layout>
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

      <!-- Analogue Network Security -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480392/StealthEntry/eccouncil/ANS_book.jpg"
                alt="book"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">Analogue Network Security</h2>
              <p class="display-1 primary--text mt-3 mb-4">$75</p>
              <p class="title text-xs-left">Analogue Network Security by Winn Schwartau</p>
              <p
                class="subheading text-xs-left"
              >Though we are offering the Analogue Network Security book as an additional resource for your cybersecurity library, the views, thoughts, and opinions expressed in the text belong solely to the author.</p>
              <p class="subheading text-xs-left">*Ships to US, Canada and Australia ONLY!</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="108"
                data-item-name="Analogue Network Security"
                data-item-price="75.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556480392/StealthEntry/eccouncil/ANS_book.jpg"
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
