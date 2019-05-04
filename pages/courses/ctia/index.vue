<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Certified Threat Intelligence Analyst (CTIA)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoCTIA" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >Certified Threat Intelligence Analyst (C|TIA) is designed and developed in collaboration with cybersecurity and threat intelligence experts across the globe to help organizations identify and mitigate business risks by converting unknown internal and external threats into known threats. It is a comprehensive, specialist-level program that teaches a structured approach for building effective threat intelligence.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >In the ever-changing threat landscape, C|TIA is an essential program for those who deal with cyber threats on a daily basis. Organizations today demand a professional-level cybersecurity threat intelligence analyst who can extract the intelligence from data by implementing various advanced strategies. Such professional-level programs can only be achieved when the core of the curricula maps with and is compliant to government and industry published threat intelligence frameworks.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Eligibility Criteria</h3>
        <p class="subheading secondary--text text-xs-left">
          Attend official EC-Council C|TIA training through an accredited EC-Council Partner (Accredited Training Center, iWeek, or iLearn) (All candidates are required to pay the USD100 application fee unless your training fee already includes this)
          <span
            class="primary--text"
          >or</span>
          Submit an application showing a minimum of 2 years working experience in information security (All candidates are required to pay USD 100 as a non-refundable application fee)
        </p>
        <a
          href="https://cert.eccouncil.org/application-process-eligibility.html"
          target="_blank"
          download
          class="text-xs-center"
        >
          <p
            class="primary--text subheading"
            style="text-decoration: underline;"
          >More Eligibility Information</p>
        </a>
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
                      <span class="font-weight-bold">Number of Questions:</span> 50
                    </p>
                    <p>
                      <span class="font-weight-bold">Passing Score:</span> 70%
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Duration:</span> 2 Hours
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Format:</span> Multiple Choice
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Delivery:</span> ECC Exam Portal
                    </p>
                  </v-flex>
                  <v-flex xs12 md6 class="secondary--text">
                    <h3 class="headline my-3">Who is it for?</h3>
                    <p>
                      Ethical Hackers,
                      Security Practitioners, Engineers, Analysts, Specialist, Architects, and Managers
                      Threat Intelligence Analysts, Associates, Researchers, Consultants,
                      Threat Hunters,
                      SOC Professionals,
                      Digital Forensic and Malware Analysts, and
                      Incident Response Team Members
                    </p>
                    <p>
                      Any mid-level to high-level cybersecurity professionals with a minimum of 2 years of experience,
                      Individuals from the information security profession and who want to enrich their skills and knowledge in the field of cyber threat intelligence, and
                      Individuals interested in preventing cyber threats.
                    </p>
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
                  justify-center
                  class="text-xs-left text-sm-center text-md-left ma-3"
                >
                  <v-flex xs12 md6 lg5 xl4 my-2>Introduction to Threat Intelligence</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Cyber Threats and Kill Chain Methodology</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Requirements, Planning, Direction, and Review</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Data Collection and Processing</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Data Analysis</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Intelligence Reporting and Dissemination</v-flex>
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
        >Choose a Training Option Below</h2>
      </v-flex>
    </v-layout>
    <CTIAiLearn :courseHome="true"/>
    <CTIAiWeek :courseHome="true"/>
    <CTIAinPerson :courseHome="true"/>

    <v-layout row wrap justify-center class="hero-background-circuit">
      <v-flex xs12 class="text-xs-center py-5">
        <h2
          class="display-1 secondary--text py-5"
        >Please contact our training team to schedule in-person live training for your Private Group</h2>
        <v-btn to="/contact" large class="orange gradient white--text">Contact Page</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Youtube from "@/components/Youtube";
import CTIAiLearn from "@/components/training/ctia/CTIAiLearn";
import CTIAiWeek from "@/components/training/ctia/CTIAiWeek";
import CTIAinPerson from "@/components/training/ctia/CTIAinPerson";

export default {
  components: {
    Youtube,
    CTIAiLearn,
    CTIAiWeek,
    CTIAinPerson
  },
  data() {
    return {
      videoCTIA: {
        id: "wAoW2mUt6p4"
      },
      videos: [
        {
          id: "JK77gJ7GSzg",
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