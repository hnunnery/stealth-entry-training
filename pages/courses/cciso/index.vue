<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Certified Chief Information Security Officer (CCISO)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoCCISO" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >The CCISO Certification is an industry-leading program that recognizes the real-world experience necessary to succeed at the highest executive levels of information security. Bringing together all the components required for a C-Level positions, the CCISO program combines audit management, governance, IS controls, human capital management, strategic program development, and the financial expertise vital to leading a highly successful IS program. The job of the CISO is far too important to be learned by trial and error. Executive level management skills are not areas that should be learned on the job.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The CCISO aims to bridge the gap between the executive management knowledge that CISOs need and the technical knowledge that many sitting and aspiring CISOs have. This can be a crucial gap as a practitioner endeavors to move from mid-management to upper, executive management roles. Much of this is traditionally learned as on the job training, but the CCISO Training Program can be the key to a successful transition to the highest ranks of information security management.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Course Information</h3>
        <p
          class="subheading secondary--text text-xs-left"
        >EC-Council’s Certified CISO Program has certified leading information security professionals around the world. A core group of high-level information security executives, the CCISO Advisory Board, formed the foundation of the program and outlined the content covered by the exam, body of knowledge, and training. Some members of the Board contributed as authors, others as exam writers, others as quality assurance checks, and still others as instructors.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Each segment of the program was developed with the aspiring and sitting CISO in mind and looks to transfer the knowledge of seasoned executives to the next generation of leaders in the areas that are most critical in the development and maintenance of a successful information security program. Material in the CCISO Program assumes a high-level understanding of technical topics and doesn’t spend much time on strictly technical information, but rather on the application of technical knowledge to an information security executive’s day-to-day work.</p>
        <a
          href="https://ciso.eccouncil.org/wp-content/uploads/2019/03/CCISO-Exam-Eligibility-Application-Form-2019.pdf"
          target="_blank"
          download
          class="text-xs-center"
        >
          <p
            class="primary--text subheading"
            style="text-decoration: underline;"
          >Download Exam Eligibility Application</p>
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
                    <p class="py-2">
                      <span class="font-weight-bold">Number of Questions:</span> 150
                    </p>
                    <p class="py-2">
                      <span class="font-weight-bold">Test Duration:</span> 2.5 Hours
                    </p>
                    <p class="py-2">
                      <span class="font-weight-bold">Test Format:</span> Multiple Choice
                    </p>
                    <p class="py-2">
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
          <!-- <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Course Outline</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout row wrap justify-center class="text-xs-left ma-3">
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 1: Computer Network and Defense Fundamentals Response & Handling</v-flex>
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 2: Network Security Threats, Vulnerabilities, and Attacks</v-flex>
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 3: Network Security Controls, Protocols, and Devices</v-flex>
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 4: Network Security Policy Design and Implementation</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 5: Physical Security</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 6: Host Security</v-flex>
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 7: Secure Firewall Configuration and Management</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 8: Secure IDS Configuration and Management</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 9: Secure VPN Configuration and Management</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 10: Wireless Network Defense</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 11: Network Traffic Monitoring and Analysis</v-flex>
                  <v-flex
                    xs12
                    md10
                    lg8
                    xl6
                    my-2
                  >Module 12: Network Risk and Vulnerability Management</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 13: Data Backup and Recovery</v-flex>
                  <v-flex xs12 md10 lg8 xl6 my-2>Module 14: Network Incident Response and Management</v-flex>
                </v-layout>
              </v-card-text>
            </v-card>
          </v-expansion-panel-content>-->
          <v-expansion-panel-content>
            <template v-slot:header>
              <h4 class="primary--text headline text-xs-center">Videos</h4>
            </template>
            <v-card>
              <v-card-text class="subheading secondary--text">
                <v-layout row wrap justify-center class="text-xs-center my-5">
                  <v-flex xs12 md6 px-2 v-for="(video, index) in videos" :key="index">
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
    <CCISOiLearn :courseHome="true"/>
    <CCISOiWeek :courseHome="true"/>
    <CCISOinPerson :courseHome="true"/>

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
import CCISOiLearn from "@/components/training/cciso/CCISOiLearn";
import CCISOiWeek from "@/components/training/cciso/CCISOiWeek";
import CCISOinPerson from "@/components/training/cciso/CCISOinPerson";

export default {
  components: {
    Youtube,
    CCISOiLearn,
    CCISOiWeek,
    CCISOinPerson
  },
  data() {
    return {
      videoCCISO: {
        id: "nG1_7I83c8s"
      },
      videos: [
        {
          id: "elRcmDLZdDw",
          title: "Meet Your Instructor"
        },
        {
          id: "JF7DhYYAePg",
          title: "What CCISO Students are Saying"
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