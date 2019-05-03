<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >EC-Council Certified Incident Handler (ECIH)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoECIH" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >The ECIH program focuses on a structured approach for performing the incident handling and response (IH&R) process. The IH&R process includes stages like incident handling and response preparation, incident validation and prioritization, incident escalation and notification, forensic evidence gathering and analysis, incident containment, systems recovery, and incident eradication. This systematic incident handling and response process creates awareness among incident responders in knowing how to respond to various types of security incidents.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Cybersecurity Professionals interested in pursuing incident handling and response as a career require comprehensive training on the IH&R concepts as well as real-world scenarios. The ECIH program includes hands-on learning delivered through iLabs, online labs within the training program.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Course Information</h3>
        <p
          class="subheading secondary--text text-xs-left"
        >EC-Council’s Certified Incident Handler provides students with a method-driven program that uses a holistic approach to cover vast concepts concerning organizational incident handling and response from preparing and planning the incident handling response process to recovering organizational assets after a security incident. The skills taught in EC-Council’s ECIH program are desired by cybersecurity professionals from around the world and is respected by employers.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The purpose of ECIH is to enable individuals and organizations with the ability to handle and respond to different types of cybersecurity incidents in a systematic way, to ensure that organization can identify, contain, and recover from an attack, to reinstate regular operations of the organization as early as possible and mitigate the negative impact on the business operations, to be able to draft security policies with efficacy and ensure that the quality of services is maintained at the agreed levels, and to minimize the loss and after-effects breach of the incident.</p>
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
                      <span class="font-weight-bold">Exam Name:</span> CEH 312-50 (ECC EXAM), 312-50 (VUE)
                    </p>
                    <p>
                      <span class="font-weight-bold">Number of Questions:</span> 125
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Duration:</span> 4 Hours
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Format:</span> Multiple Choice
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Delivery:</span> ECC EXAM, VUE
                    </p>
                  </v-flex>
                  <v-flex xs12 md6 class="secondary--text">
                    <h3 class="headline my-3">Passing Score</h3>
                    <p>In order to maintain the high integrity of our certifications exams, EC-Council Exams are provided in multiple forms (I.e. different question banks). Each form is carefully analyzed through beta testing with an appropriate sample group under the purview of a committee of subject matter experts that ensure that each of our exams not only has academic rigor but also has “real world” applicability. We also have a process to determine the difficulty rating of each question. The individual rating then contributes to an overall "Cut Score" for each exam form. To ensure each form has equal assessment standards, cut scores are set on a "per exam form" basis. Depending on which exam form is challenged, cut scores can range from 60% to 85%</p>
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
                  <v-flex xs12 md6 my-2>Module 01: Introduction to Incident Handling and Response</v-flex>
                  <v-flex xs12 md6 my-2>Module 02: Incident Handling and Response Process</v-flex>
                  <v-flex xs12 md6 my-2>Module 03: Forensic Readiness and First Response</v-flex>
                  <v-flex xs12 md6 my-2>Module 04: Handling and Responding to Malware Incidents</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 05: Handling and Responding to Email Security Incidents</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 06: Handling and Responding to Network Security Incidents</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 07: Handling and Responding to Web Application Security Incidents</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 08: Handling and Responding to Cloud Security Incidents</v-flex>
                  <v-flex xs12 md6 my-2>Module 09: Handling and Responding to Insider Threats</v-flex>
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
    <ECIHiLearn :courseHome="true"/>
    <ECIHiWeek :courseHome="true"/>
    <ECIHinPerson :courseHome="true"/>

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
import ECIHiLearn from "@/components/training/ECIH/ECIHiLearn";
import ECIHiWeek from "@/components/training/ECIH/ECIHiWeek";
import ECIHinPerson from "@/components/training/ECIH/ECIHinPerson";

export default {
  components: {
    Youtube,
    ECIHiLearn,
    ECIHiWeek,
    ECIHinPerson
  },
  data() {
    return {
      videoECIH: {
        id: "2LeR7Yxrfls"
      },
      videos: [
        {
          id: "KiQ1MeDTeuU",
          title: "Meet Your Instructor"
        },
        {
          id: "iU_7zKypJZI",
          title: "iLabs Demo"
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