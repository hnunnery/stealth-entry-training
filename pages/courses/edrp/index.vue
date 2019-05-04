<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >EC-Council Disaster Recovery Professional (EDRP)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoEDRP" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >EC Council Disaster Recovery Professional (EDRP) is a compressive professional course that teaches students how to develop enterprise-wide business continuity and disaster recovery plans. It teaches professionals various methods of identifying vulnerabilities and taking countermeasures against the said vulnerabilities. The professionals will learn how to secure their data by putting policies and procedures in place, and how to recover and restore their organization’s critical data in the aftermath of a disaster.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >EDRP provides the professionals with a strong understanding of business continuity and disaster recovery principles, including conducting business impact analysis, assessing of risks, developing policies and procedures, and implementing a plan.</p>
      </v-flex>
    </v-layout>

    <v-layout justify-center mb-5>
      <v-flex xs12 lg11 xl10 class="elevation-12">
        <v-expansion-panel v-model="panel" expand>
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">About the Exam</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout row wrap justify-center class="text-xs-left">
                  <v-flex xs12 md6 lg4>
                    <h3 class="headline my-3">Exam Details</h3>
                    <p>
                      <span class="font-weight-bold">Number of Questions:</span> 150
                    </p>
                    <p>
                      <span class="font-weight-bold">Passing Score:</span> 70%
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Duration:</span> 4 Hours
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Format:</span> Multiple Choice
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Delivery:</span> ECC Exam Portal
                    </p>
                  </v-flex>
                  <v-flex xs12 md6 class="secondary--text">
                    <h3 class="headline my-3">Why EDRP?</h3>
                    <p>EDRP covers all the relevant knowledge-bases and skills to meets with regulatory compliance standards such as ISO 27001, ISO 22301, ISO 22313, NFPA 1600, ISO/ IEC 27005, ISO 31000, ISO 31010, INCITS 483-2012, and the NICE Framework</p>
                    <p>The program is developed after a thorough job task analysis and market research. The course is designed and developed by experienced SMEs and business continuity/ disaster recovery experts.</p>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Course Outline</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout
                  row
                  wrap
                  justify-left
                  class="text-xs-left text-sm-center text-md-left ma-3"
                >
                  <v-flex xs12 my-2>
                    <p class="text-xs-center">
                      <span class="font-weight-bold">Prerequisite:</span> Min 2 yrs experience in the BC/DR domain
                    </p>
                  </v-flex>
                  <v-flex xs12 md6 lg4 my-2>Disaster Recovery and Business Continuity</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Business Continuity Management</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Risk Assessment</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Business Impact Analysis</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Business Continuity Plan</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Data Backup</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Data Recovery Strategies</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Virtualization Bases Disaster Recovery</v-flex>
                  <v-flex xs12 md6 lg4 my-2>System Recovery</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Centralized and Decentralized Computing</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Disaster Recovery Planning Process</v-flex>
                  <v-flex xs12 md6 lg4 my-2>BCP Testing, Maintenance, and Training</v-flex>
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
                <v-layout row wrap justify-space-around class="text-xs-center my-5">
                  <v-flex xs12 md6 lg3 px-2 v-for="(video, index) in videos" :key="index">
                    <Youtube :video="video"/>
                  </v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-flex>
    </v-layout>

    <v-layout row wrap justify-center>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-up"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Only Available in Self-Paced</h2>
      </v-flex>
    </v-layout>
    <EDRPiLearnPurchase/>
    <AddOns/>
  </v-container>
</template>

<script>
import Youtube from "@/components/Youtube";
import EDRPiLearnPurchase from "@/components/training/edrp/EDRPiLearnPurchase";
import AddOns from "@/components/training/edrp/AddOns";

export default {
  components: {
    Youtube,
    EDRPiLearnPurchase,
    AddOns
  },
  data() {
    return {
      videoEDRP: {
        id: "vHjq8NOtWNs"
      },
      videos: [
        {
          id: "q_voS3fjTQc",
          title: "Meet Your Instructor"
        },
        {
          id: "iU_7zKypJZI",
          title: "iLabs Demo"
        }
      ],
      panel: [true, false, false]
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