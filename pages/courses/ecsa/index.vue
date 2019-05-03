<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >EC-Council Certified Security Analyst (ECSA)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoECSA" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >The ECSA course is a fully hands-on program with labs and exercises that cover real world scenarios. By practicing the skills that are provided to you in the ECSA class, we are able to bring you up to speed with the skills to uncover the security threats that organizations are vulnerable to.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >This can be achieved effectively with the EC-Council iLabs Cyber Range. It allows you to dynamically access a host of Virtual Machines preconfigured with vulnerabilities, exploits, tools, and scripts from anywhere with an internet connection.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Our guided step-by-step labs include exercises with detailed tasks, supporting tools, and additional materials allowing you to launch a complete live range for any form of hacking or testing.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Course Information</h3>
        <p
          class="subheading secondary--text text-xs-left"
        >The ECSA program offers a seamless learning progress continuing where the CEH program left off. The new ECSAv10 includes updated curricula and an industry recognized comprehensive step-bystep penetration testing methodology. This allows a learner to elevate their ability in applying new skills learned through intensive practical labs and challenges.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Unlike most other pen testing programs that only follow a generic kill chain methodology; the ECSA presents a set of distinguishable comprehensive methodologies that are able to cover different pentesting requirements across different verticals. It is a highly interactive, comprehensive, standards based, intensive 5-days training program that teaches information security professionals how professional real-life penetration testing are conducted. Building on the knowledge, skills and abilities covered in the new CEH v10 program, we have simultaneously re engineered the ECSA program as a progression from the former.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Organizations today demand a professional level pentesting program and not just pentesting programs that provide training on how to hack through applications and networks. Such professional level programs can only be achieved when the core of the curricula maps with and is compliant to government and/or industry published pentesting frameworks. This course is a part of the VAPT Track of EC-Council. This is a “Professional” level course, with the Certified Ethical Hacker being the “Core” and the Licensed Penetration Tester being the “Master” level certification.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >In the new ECSAv10 course, students that passes the knowledge exam are given an option to pursue a fully practical exam that provides an avenue for them to test their skills, earning them the ECSA (Practical) credential. This new credential allows employers to validate easily the skills of the student.</p>
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
                <v-layout row wrap justify-space-around class="text-xs-left">
                  <v-flex xs12 md6 lg5 xl4>
                    <h3 class="headline my-3">Exam Details</h3>
                    <p>
                      <span class="font-weight-bold">Exam Name:</span> ECSA
                    </p>
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
                  <v-flex xs12 md6 lg5 xl4 class="secondary--text">
                    <h3 class="headline my-3">Who is it for?</h3>
                    <p>Ethical Hackers</p>
                    <p>Penetration Testers</p>
                    <p>Network server administrators</p>
                    <p>Firewall Administrators</p>
                    <p>Security Testers</p>
                    <p>System Administrators and Risk Assessment professionals</p>
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
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 00: Penetration Testing Essential Concepts (Self-Study)</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 01: Introduction to Penetration Testing and Methodologies</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 02: Penetration Testing Scoping and Engagement Methodology</v-flex>
                  <v-flex xs12 md6 my-2>Module 03: Open-Source Intelligence (OSINT) Methodology</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 04: Social Engineering Penetration Testing Methodology</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 05: Network Penetration Testing Methodology – External</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 06: Network Penetration Testing Methodology – Internal</v-flex>
                  <v-flex
                    xs12
                    md6
                    my-2
                  >Module 07: Network Penetration Testing Methodology – Perimeter Devices</v-flex>
                  <v-flex xs12 md6 my-2>Module 08: Web Application Penetration Testing Methodology</v-flex>
                  <v-flex xs12 md6 my-2>Module 09: Database Penetration Testing Methodology</v-flex>
                  <v-flex xs12 md6 my-2>Module 10: Wireless Penetration Testing Methodology</v-flex>
                  <v-flex xs12 md6 my-2>Module 11: Cloud Penetration Testing Methodology</v-flex>
                  <v-flex xs12 md6 my-2>Module 12: Report Writing and Post Testing Actions</v-flex>
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
              <h4 class="primary--text headline text-xs-center">ECSA Practical</h4>
            </template>
            <v-card>
              <v-card-text>
                <v-layout row wrap justify-center class="text-xs-left">
                  <v-flex xs12 lg10 class="subheading secondary--text">
                    <h4
                      class="headline text-xs-center mt-1 mb-3"
                    >About the EC-Council Certified Security Analyst (Practical)</h4>
                    <p>
                      ECSA (Practical) is a 12-hour, rigorous practical exam built to test your penetration testing skills.
                      ECSA (Practical) presents you with an organization and its network environment, containing multiple hosts. The internal network consists of several subnets housing various organizational units. It is made up of militarized and demilitarized zones, connected with a huge pool of database servers in a database zone. As a security precaution, and by design, all the internal resource zones are confi­gured with different subnet IPs. The militarized zone houses the domain controllers and application servers that provide application frameworks for various departments of the organization.
                    </p>
                    <p>The candidates are required to demonstrate the application of the penetration testing methodology that is presented in the ECSA program, and are required to perform a comprehensive security audit of an organization, just like in the real world. You will start with challenges requiring you to perform advanced network scans beyond perimeter defenses, leading to automated and manual vulnerability analysis, exploit selection, customization, launch, and post exploitation maneuvers.</p>
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
    <ECSAiLearn :courseHome="true"/>
    <ECSAiWeek :courseHome="true"/>
    <ECSAinPerson :courseHome="true"/>

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
import ECSAiLearn from "@/components/training/ecsa/ECSAiLearn";
import ECSAiWeek from "@/components/training/ecsa/ECSAiWeek";
import ECSAinPerson from "@/components/training/ecsa/ECSAinPerson";

export default {
  components: {
    Youtube,
    ECSAiLearn,
    ECSAiWeek,
    ECSAinPerson
  },
  data() {
    return {
      videoECSA: {
        id: "kbJXIt9aqMs"
      },
      videos: [
        {
          id: "kbJXIt9aqMs",
          title: "ECSA Course Demo"
        },
        {
          id: "6WMOkjUI6e8",
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