<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Computer Hacking Forensic Investigator (CHFI)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoCHFI" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >The Computer Hacking Forensic Investigator (CHFI) course delivers the security discipline of digital forensics from a vendor-neutral perspective. CHFI is a comprehensive course covering major forensic investigation scenarios and enabling students to acquire necessary hands-on experience with various forensic investigation techniques and standard forensic tools necessary to successfully carry out a computer forensic investigation leading to the prosecution of perpetrators.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The CHFI certification gives participants (Law enforcement personnel, system administrators, security officers, defense and military personnel, legal professionals, bankers, security professionals, and anyone who is concerned about the integrity of the network infrastructure.) the necessary skills to perform an effective digital forensics investigation.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Course Information</h3>
        <p
          class="subheading secondary--text text-xs-left"
        >CHFI presents a methodological approach to computer forensics including searching and seizing, chain-of-custody, acquisition, preservation, analysis and reporting of digital evidence. The course was designed and developed by experienced SMEs and digital forensics practitioners. It is a complete vendor neutral course covering all major forensics investigations technologies and solutions. Detailed labs for hands-on learning experience; approximately 50% of training time is dedicated to labs. The course covers all the relevant knowledge-bases and skills to meets with regulatory compliance standards such as ISO 27001, PCI DSS, SOX, and HIPPA. The program presents a repeatable forensics investigation methodology required from a versatile digital forensic professional which increases your employability.</p>
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
                      <span class="font-weight-bold">Exam Name:</span> CHFI EC0 312-49
                    </p>
                    <p>
                      <span class="font-weight-bold">Number of Questions:</span> 150
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
                    <h3 class="headline my-3">Passing Score</h3>
                    <p>In order to maintain the high integrity of our certifications exams, EC-Council Exams are provided in multiple forms (I.e. different question banks). Each form is carefully analyzed through beta testing with an appropriate sample group under the purview of a committee of subject matter experts that ensure that each of our exams not only has academic rigor but also has “real world” applicability. We also have a process to determine the difficulty rating of each question. The individual rating then contributes to an overall "Cut Score" for each exam form. To ensure each form has equal assessment standards, cut scores are set on a "per exam form" basis. Depending on which exam form is challenged, cut scores can range from 60% to 78%.</p>
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
                  <v-flex xs12 md6 lg4 my-2>Computer Forensics in Today’s World</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Computer Forensics Investigation Process</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Understanding Hard Disks and File Systems</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Operating System Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Defeating Anti-forensics Techniques</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Data Acquisition and Duplication</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Network Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Investigating Web Attacks</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Database Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Cloud Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Malware Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Investigating Email Crimes</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Mobile Forensics</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Investigative Reports</v-flex>
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
    <CHFIiLearn :courseHome="true"/>
    <CHFIiWeek :courseHome="true"/>
    <CHFIinPerson :courseHome="true"/>

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
import CHFIiLearn from "@/components/training/CHFI/CHFIiLearn";
import CHFIiWeek from "@/components/training/CHFI/CHFIiWeek";
import CHFIinPerson from "@/components/training/CHFI/CHFIinPerson";

export default {
  components: {
    Youtube,
    CHFIiLearn,
    CHFIiWeek,
    CHFIinPerson
  },
  data() {
    return {
      videoCHFI: {
        id: "c3MIZI8MgWM"
      },
      videos: [
        {
          id: "dfK_vECvUSg",
          title: "Computer Hacking Forensic Investigator (CHFI)"
        },
        {
          id: "rFk3R5fbixQ",
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