<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >STORM - Mobile Security Tool kit</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoSTORM" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >EC-Council’s Mobile Security Toolkit (Better known as the STORM!) is a fully-loaded pen-test platform which comes equipped with STORM Linux (a Raspbian based, customized distro of Linux equipped with the industry’s most popular hacking tools) loaded onto a portable touchscreen device.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The STORM mobile security tool kit contains the STORM Linux (a Raspbian based, customized distro of Linux) including all of the associated security tools. These tools are very powerful and all proper precautions should be adhered to at all times. Always remember that the difference between illegal and ethical hacking comes down to one word; permission. It is illegal to utilize these or any other pen testing tools on a network or website without permission.</p>
      </v-flex>
    </v-layout>

    <v-layout justify-center mb-5>
      <v-flex xs12 lg11 xl10 class="elevation-12">
        <v-expansion-panel v-model="panel" expand>
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Toolkit Contents</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout row wrap justify-center align-center>
                  <v-flex xs12 lg10>
                    <v-layout row wrap justify-left class="text-xs-left">
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >64 Bit – Quad Core Mobile System with Case</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">1 GB RAM</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">7 inch touch screen display</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >4 GB MicroSD – Preloaded w/Custom Linux Hacking OS</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">100Mb Ethernet port</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">4 USB ports</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">802.11n wireless</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">Bluetooth 4.1</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >Combined 3.5mm audio jack and composite video</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">Camera interface (CSI)</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">Display interface (DSI)</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >VideoCore IV 3D graphics core</v-flex>
                      <v-flex xs12 md6 lg4 my-2 class="secondary--text">Full HDMI</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >USB 2.0 A to B Micro Power Cable</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >Rollup water resistant keyboard</v-flex>
                      <v-flex
                        xs12
                        md6
                        lg4
                        my-2
                        class="secondary--text"
                      >Field Case Organizer for all your gear</v-flex>
                    </v-layout>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Videos</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout row wrap justify-center class="text-xs-center my-5">
                  <v-flex xs12 md6 lg3 px-2 v-for="(video, index) in videos" :key="index">
                    <Youtube :video="video"/>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Testimonials</h4>
            </template>
            <v-card>
              <v-card-text>
                <v-layout row wrap justify-center class="text-xs-left">
                  <v-flex xs12 lg10 class="subheading secondary--text">
                    <p>“I really enjoyed the class, thanks for working with the chapter to get this delivered to the group. Hope we can do something similar next year.” – Anne-Marie Colombo, SAP</p>
                    <p>“It was a smashing success. In January we should have you talk to the ISSA Board and see how we do more.” – Justin Orcutt, NCC Group</p>
                    <p>“Everyone enjoyed what EC-Council brought to BSides Huntsville! The STORM Device is so cool and we have attracted a new audience because of EC-Council” – Cary Pool, NAISSA President</p>
                    <p>“I’ve taken all of EC-Council Courses at TakeDownCon. This was a nice addition to BSides and it was great to sit in a new EC-Council Class and learn a new device!” – Chad Holton, State of AL Alcoholic Beverage Control Board</p>
                    <p>“It was my first time working with EC-Council and It was great to bring a workshop from such a reputable certification body, this added tremendous value to BSides Tampa and I look forward to working with you all again in 2019!”- Derek Thomas, BSides Tampa Organizer</p>
                    <p>“The HACKNYC 2018 event has truly changed my Information Security outlook and has greatly improved my overall skills in every aspect. Connecting with Elite Cyber Security Professionals in the private sector and federal government to the 2-day “all-out” Mobile Security Hacking with the Storm Tool in conjunction with the iLabs, and Kevin Cardwell (my trainer) made this a true exceptional Cyber Security training and experience.</p>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Youtube from "@/components/Youtube";

export default {
  components: {
    Youtube
  },
  data() {
    return {
      videoSTORM: {
        id: "6ikIAce7zrg"
      },
      videos: [
        {
          id: "65IntFqlL6U",
          title: "Mobile Security Toolkit Workshop"
        },
        {
          id: "8SReC5lVpSc",
          title: "Take Your Hacking by STORM"
        },
        {
          id: "JK0nMziou9k",
          title: "Hack Like the Pros"
        }
      ],
      panel: [true, false, false, false]
    };
  }
};
</script>

<style lang="scss" scoped>
.padding {
  padding-left: 15px !important;
  padding-right: 15px !important;
}
@media screen and (min-width: 600px) {
  .padding {
    padding-left: 50px !important;
    padding-right: 50px !important;
  }
}
@media screen and (max-width: 599px) {
  .my-title {
    font-size: 2.5em !important;
  }
}
</style>