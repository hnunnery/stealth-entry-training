<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Certified Ethical Hacker v10 (CEH)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center mt-5>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <Youtube :video="videoCEH" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >The Certified Ethical Hacker (CEH v10) program is a trusted and respected ethical hacking training Program that any information security professional will need. Since its inception in 2003, the Certified Ethical Hacker has been the absolute choice of the industry globally. It is a respected certification in the industry and is listed as a baseline certification on the United States Department of Defense Directive 8570. The CEH exam is ANSI 17024 compliant adding credibility and value to credential members.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >CEH is used as a hiring standard and is a core sought-after certification by many of the Fortune 500 organizations, governments, cybersecurity practices, and a cyber staple in education across many of the most prominent degree programs in top Universities around the globe. Cyber Security as a profession is evolving, the barrier to entry is rising, the demand for Skilled Cyber professionals continues to grow, but it is being refined, demanding a higher level of skill and ability.</p>
      </v-flex>
      <v-flex xs12 xl10 mb-5 class="padding">
        <h3 class="headline primary--text text-xs-center mb-3">Course Information</h3>
        <p
          class="subheading secondary--text text-xs-left"
        >The worlds most advanced ethical hacking course with 20 of the most current security domains an ethical hacker will want to know when planning to beef up the information security posture of their organization. In 20 comprehensive modules, the course covers over 270 attack technologies, commonly used by hackers.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Our security experts have designed over 140 labs which mimic real time scenarios in the course to help you “live” through an attack as if it were real and provide you with access to over 2200 commonly used hacking tools to immerse you into the hacker world.</p>
        <p
          class="subheading secondary--text text-xs-left"
        >The goal of this course is to help you master an ethical hacking methodology that can be used in a penetration testing or ethical hacking situation. You walk out the door with ethical hacking skills that are highly in demand, as well as the globally recognized Certified Ethical Hacker certification!</p>
        <a
          href="https://www.eccouncil.org/wp-content/uploads/2016/07/CEHv10-Brochure.pdf"
          target="_blank"
          download
          class="text-xs-center"
        >
          <p class="primary--text subheading" style="text-decoration: underline;">Download Brochure</p>
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
                  <v-flex xs12 md6 lg4 my-2>Introduction to Ethical Hacking</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Footprinting and Reconnaissance</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Scanning Networks</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Enumeration</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Vulnerability Analysis</v-flex>
                  <v-flex xs12 md6 lg4 my-2>System Hacking</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Malware Threats</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Sniffing</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Social Engineering</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Denial-of-Service</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Session Hijacking</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Evading IDS, Firewalls, and Honeypots</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Hacking Web Servers</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Hacking Web Applications</v-flex>
                  <v-flex xs12 md6 lg4 my-2>SQL Injection</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Hacking Wireless Networks</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Hacking Mobile Platforms</v-flex>
                  <v-flex xs12 md6 lg4 my-2>IoT Hacking</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Cloud Computing</v-flex>
                  <v-flex xs12 md6 lg4 my-2>Cryptography</v-flex>
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
              <h4 class="primary--text headline text-xs-center">CEH Practical</h4>
            </template>
            <v-card>
              <v-card-text>
                <v-layout row wrap justify-center class="text-xs-left">
                  <v-flex xs12 lg10 class="subheading secondary--text">
                    <h4
                      class="headline text-xs-center mt-1 mb-3"
                    >About the Certified Ethical Hacker (Practical)</h4>
                    <p>CEH Practical is a six-hour, rigorous exam that requires you to demonstrate the application of ethical hacking techniques such as threat vector identification, network scanning, OS detection, vulnerability analysis, system hacking, web app hacking, etc. to solve a security audit challenge.</p>
                    <p>This is the next step after you have attained the highly acclaimed Certified Ethical Hacker certification. Professionals that possess the C|EH credential will be able to sit for exam that will test them to their limits in unearthing vulnerabilities across major operating systems, databases, and networks.</p>
                    <p>You will be given limited time, just like in the real world. The exam was developed by a panel of experienced SMEs and includes 20 real-life scenarios with questions designed to validate essential skills required in the ethical hacking domains as outlined in the C|EH program.</p>
                    <p>It is not a simulated exam but rather, it mimics a real corporate network through the use of live virtual machines, networks, and applications, designed to test your skills. You will be presented with scenarios and will be asked to demonstrate the application of the knowledge acquired in the C|EH course to find solutions to real-life challenges.</p>
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
    <CEHiLearn :courseHome="true"/>
    <CEHiWeek :courseHome="true"/>
    <CEHinPerson :courseHome="true"/>

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
import CEHiLearn from "@/components/training/ceh/CEHiLearn";
import CEHiWeek from "@/components/training/ceh/CEHiWeek";
import CEHinPerson from "@/components/training/ceh/CEHinPerson";

export default {
  components: {
    Youtube,
    CEHiLearn,
    CEHiWeek,
    CEHinPerson
  },
  data() {
    return {
      videoCEH: {
        id: "MrJj9kRFPO0"
      },
      videos: [
        {
          id: "1BO3FVZZAWU",
          title: "What Our Student Say"
        },
        {
          id: "L6dofrkRohA",
          title: "Can You Spot the Hacker"
        },
        {
          id: "iU_7zKypJZI",
          title: "iLabs Demo"
        },
        {
          id: "3l0e8h9jRNw",
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