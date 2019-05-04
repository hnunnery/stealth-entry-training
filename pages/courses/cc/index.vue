<template>
  <v-container fluid pa-0>
    <v-layout>
      <v-flex xs12 class="py-4 px-2 orange elevation-12">
        <h2
          class="display-2 white--text text-xs-center my-title"
          data-aos="zoom-out-down"
          data-aos-delay="100"
          data-aos-duration="1000"
        >Core Concepts (of CEH)</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center align-center my-5>
      <v-flex xs12 md5 xl4 mb-4 class="padding">
        <v-img
          src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556998753/StealthEntry/eccouncil/CoreConcepts-cover-main-300x300.jpg"
          alt="CC"
          class="responsive-img"
          max-height="400"
          contain
        ></v-img>
      </v-flex>
      <v-flex xs12 md6 xl5 mb-4 class="padding">
        <p
          class="subheading secondary--text text-xs-left"
        >In this course you will learn the core skills to build a solid security foundation. You will examine in detail the traffic that traverses the network at the packet and binary level. You will build solid knowledge on the lowest layers of the network. In the course you will conduct extensive hands-on exercises. You will learn to master the TCP/IP protocol. You will learn essential UNIX and Linux survival skills that separate you from the many security professionals who are Windows centric..</p>
        <p
          class="subheading secondary--text text-xs-left"
        >Additionally, you will be introduced to vulnerability assessment and the hacking methodology. When you finish this course you will have a solid security foundation to pursue more advanced security training. For many, when you take a class like the Certified Ethical Hacker (CEH) you have not established the foundation that is needed to get the most from the course, this is where the Core Concepts course comes in, it is the bridge between a beginning level security course and CEH; furthermore, it focus on the main concepts required to build a foundation in security.</p>
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
                  <v-flex xs12 lg10 xl8 class="secondary--text">
                    <h3 class="headline my-3">Why Core Concepts?</h3>
                    <p>To gain the skills needed to move on to more advanced security topics. The majority of professionals entering the field will lack the foundation that this course will bring. Take the free evaluation test and if the majority of the questions are new to you and the answers are unknown you would benefit greatly from taking this class.</p>
                    <h3 class="headline my-3">Who is it for?</h3>
                    <p>This course is for anyone who wants to start out with the foundation and core concept skills for becoming a security professional. By taking this course you will learn the foundations of security to include in-depth knowledge of the TCP/IP protocol.</p>
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
                  <v-flex
                    xs12
                    md6
                    lg5
                    xl4
                    my-2
                  >Module 1: Introduction to Required Skills for Security</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 2: Introduction & Overview</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 3: UNIX/Linux</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 4: Introducing Linux</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 5: Overview of Virtual Machines</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 6: Introduction to Vulnerability Assessment</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 7: Hacking Process & Methodology</v-flex>
                  <v-flex xs12 md6 lg5 xl4 my-2>Module 8: Challenges of Staying Current</v-flex>
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
    <CCiLearnPurchase/>
    <AddOns/>
  </v-container>
</template>

<script>
import Youtube from "@/components/Youtube";
import CCiLearnPurchase from "@/components/training/cc/CCiLearnPurchase";
import AddOns from "@/components/training/cc/AddOns";

export default {
  components: {
    Youtube,
    CCiLearnPurchase,
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