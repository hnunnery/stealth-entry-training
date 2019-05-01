<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Certified Network Defender (CND)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoCND" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >Certified Network Defender (CND) is a vendor-neutral, hands-on, instructor-led comprehensive network security certification training program. It is a skills-based, lab intensive program based on a job-task analysis and cybersecurity education framework by the National Initiative of Cybersecurity Education (NICE). The course has also been mapped to global job roles and to the Department of Defense (DoD) job roles for system/network administrators.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The program prepares network administrators on network security technologies and operations to attain Defense-in-Depth network security preparedness. It covers the protect, detect and respond approach to network security. The course contains hands-on labs, based on major network security tools and techniques which will provide network administrators real world expertise on current network security technologies and operations. The study-kit provides over 10 GB of network security best practices, assessments and protection tools. The kit also contains templates for various network policies and white papers for additional learning.</p>
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
                      <span class="font-weight-bold">Exam Name:</span> CND (312-38) Exam
                    </p>
                    <p>
                      <span class="font-weight-bold">Number of Questions:</span> 100
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Duration:</span> 4 Hours
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Format:</span> Interactive Multiple Choice Questions
                    </p>
                    <p>
                      <span class="font-weight-bold">Test Delivery:</span> ECC EXAM
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
    <CNDiLearn :courseHome="true"/>
    <CNDiWeek :courseHome="true"/>
    <CNDinPerson :courseHome="true"/>

    <v-layout row wrap justify-center>
      <v-flex xs12 class="text-xs-center py-5">
        <h2 class="display-1 secondary--text py-5">
          Please contact our training team to
          <span class="primary--text">Schedule</span> in-person live training for your
          <span class="primary--text">Private Group</span>
        </h2>
        <v-btn to="/contact" large class="orange gradient white--text">Contact Page</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Youtube from "@/components/Youtube";
import CNDiLearn from "@/components/training/cnd/CNDiLearn";
import CNDiWeek from "@/components/training/cnd/CNDiWeek";
import CNDinPerson from "@/components/training/cnd/CNDinPerson";

export default {
  components: {
    Youtube,
    CNDiLearn,
    CNDiWeek,
    CNDinPerson
  },
  data() {
    return {
      videoCND: {
        id: "CeqtOuBj9w8"
      },
      videos: [
        {
          id: "Db1SC239yuk",
          title: "CND with Eric Reed"
        },
        {
          id: "iU_7zKypJZI",
          title: "iLabs Demo"
        },
        {
          id: "yHxUu4ciMCA",
          title: "Meet Your Instructor"
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