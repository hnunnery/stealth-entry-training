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

      <!-- CCISO Textbook -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753210/StealthEntry/eccouncil/CCISO-cover.png"
                alt="textbook"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">CCISO Textbook</h2>
              <p class="display-1 primary--text mt-3 mb-4">$250</p>
              <p class="subheading text-xs-center">Textbook for Certified Ethical Hacker (CEH)</p>
              <p class="text-xs-center">*Note: Ships to US, Canada and Australia ONLY!</p>
              <p class="subheading text-xs-center">
                Regular Price: $527
                <span class="primary--text">(Only $250 when buying the course)</span>
              </p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="114"
                data-item-name="CCISO Textbook"
                data-item-price="250.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753210/StealthEntry/eccouncil/CCISO-cover.png"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- CISO Defenders Book -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753308/StealthEntry/eccouncil/image1-1.jpg"
                alt="textbook"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2
                class="display-1 secondary--text pt-4"
              >CISO Defenders of the Cyber Realm: Dirty Deeds, Hackers & Heroes</h2>
              <p class="display-1 primary--text mt-3 mb-4">$35</p>
              <p class="subheading text-xs-center">Signed by Author Mike Loginov</p>
              <p
                class="subheading text-xs-left"
              >Though we are offering the Analogue Network Security book as an additional resource for your cybersecurity library, the views, thoughts, and opinions expressed in the text belong solely to the author.</p>
              <p class="text-xs-center">*Note: Ships to US, Canada and Australia ONLY!</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="115"
                data-item-name="CISO Defenders of the Cyber Realm"
                data-item-price="35.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753308/StealthEntry/eccouncil/image1-1.jpg"
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

      <!-- CCISO Textbook -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753219/StealthEntry/eccouncil/CCISO-mugs.jpg"
                alt="textbook"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">CCISO Coffee Mug</h2>
              <p class="display-1 primary--text mt-3 mb-4">$15</p>
              <p
                class="subheading text-xs-center"
              >Certified Chief Information Security Officer Coffee Mug</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="116"
                data-item-name="CCISO Coffee Mug"
                data-item-price="15.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753219/StealthEntry/eccouncil/CCISO-mugs.jpg"
                data-item-url="/products.json"
              >Add to Cart</v-btn>
            </v-flex>
          </v-layout>
        </v-card>
      </v-flex>

      <!-- CCISO Textbook -->
      <v-flex xs12 lg10 xl8 my-4>
        <v-card class="secondary--text text-xs-center py-3 elevation-12">
          <v-layout row wrap justify-center align-center>
            <v-flex xs12 lg5 px-4>
              <v-img
                src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753222/StealthEntry/eccouncil/CISO-Mugs-new-1.jpg"
                alt="textbook"
                class="responsive-img"
                max-height="500"
                contain
              ></v-img>
            </v-flex>
            <v-flex xs12 lg6 px-4>
              <h2 class="display-1 secondary--text pt-4">Global CISO Forum Mug</h2>
              <p class="display-1 primary--text mt-3 mb-4">$15</p>
              <p
                class="subheading text-xs-center"
              >Global Chief Information Security Officer Forum Mug</p>
              <v-btn
                large
                class="snipcart-add-item primary gradient mb-4"
                data-item-id="117"
                data-item-name="Global CISO Forum Mug"
                data-item-price="15.00"
                data-item-image="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556753222/StealthEntry/eccouncil/CISO-Mugs-new-1.jpg"
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
