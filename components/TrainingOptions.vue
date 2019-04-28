<template>
  <v-container fluid pt-5 px-0>
    <v-layout row wrap justify-center align-center>
      <v-flex xs12 md6 class="text-xs-center padding">
        <h2 class="display-2 primary--text">iClass is EC-Council’s Official Delivery Platform</h2>
        <p
          class="headline secondary--text text-xs-left mt-4 mb-5"
          style="line-height: 1.7em !important;"
        >What that means is that if you choose to attend iClass training, your exam will be included in the package and you will not have to apply and prove 2 years of IT Security experience in order to test!</p>
      </v-flex>
      <v-flex xs12 md6 class="text-xs-center mb-5 padding">
        <Youtube :video="video" class="elevation-12"/>
      </v-flex>
      <v-flex xs12 class="text-xs-center orange py-5 padding elevation-12">
        <h5
          class="display-1 white--text"
        >In the iClass platform we offer a few different ways in which you can train.</h5>
      </v-flex>
    </v-layout>
    <v-layout row wrap justify-center>
      <!-- Self-Paced -->
      <v-flex xs12 lg6 class="text-xs-center my-5 spread">
        <v-card to="/courses/iclass" class="padding py-4 my-card elevation-12">
          <v-img
            src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134826/StealthEntry/eccouncil/self-paced.png"
            width="100"
            style="margin: 0 auto;"
          ></v-img>
          <h2 class="display-1 primary--text mt-2 mb-4">Self-Paced</h2>
          <p
            class="subheading secondary--text text-xs-left"
          >This solution is an asynchronous, self-study environment which delivers EC-Council’s sought after IT Security training courses, such as CEH, in a streaming video format. All lectures are delivered by a professional practitioner to assure a real-world perspective on the course concepts.</p>
          <p
            class="subheading secondary--text text-xs-left"
          >This all-inclusive training program provides the benefits of classroom training at your own pace.</p>
          <p class="subheading secondary--text text-xs-left font-weight-bold">Base package includes:</p>
          <ul class="subheading secondary--text text-xs-left">
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Instructor-led, streaming video training modules – 1 year access
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Official EC-Council e-courseware – 1 year access
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; iLabs, virtual lab platform – 6 months access
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Certificate of Attendance
            </li>
          </ul>
        </v-card>
      </v-flex>

      <!-- In-Person -->
      <v-flex xs12 lg6 class="text-xs-center my-5 spread">
        <v-card to="/courses/in-person" class="padding py-4 my-card elevation-12">
          <v-img
            src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134826/StealthEntry/eccouncil/in-person.png"
            width="100"
            style="margin: 0 auto;"
          ></v-img>
          <h2 class="display-1 primary--text mt-2 mb-4">In-Person</h2>
          <p
            class="subheading secondary--text text-xs-left"
          >EC-Council offers “In-Person” training, in cities throughout North America. Instructor-led training in your own town is offered to provide you world class instruction conveniently located in your backyard, and since the course is live, you will collaborate with your peers and gain real-world skills while receiving in-person instruction and interaction.</p>
          <p
            class="subheading secondary--text text-xs-left"
          >We only employ subject matter experts (SMEs) to teach our courses so you will learn from a practitioner rather than someone who prepped on Friday for a class on Monday. In-person training comes with our industry changing iLabs, online labs platform, a choice of testing on the final day of class or online anytime with a web-based proctor.</p>
          <p class="subheading secondary--text text-xs-left font-weight-bold">Training includes:</p>
          <ul class="subheading secondary--text text-xs-left">
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Official Courseware
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; iLabs, Online Labs (6 Months Access)
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Test Prep Program (CEH only)
            </li>
          </ul>
        </v-card>
      </v-flex>

      <!-- Live Online -->
      <v-flex xs12 lg6 class="text-xs-center my-5 spread">
        <v-card to="/courses/iweek" class="padding py-4 my-card-2 elevation-12">
          <v-img
            src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1551134826/StealthEntry/eccouncil/online.png"
            width="100"
            style="margin: 0 auto;"
          ></v-img>
          <h2 class="display-1 primary--text mt-2 mb-4">Live Online</h2>
          <p
            class="subheading secondary--text text-xs-left"
          >This solution is a live, online, instructor-led training course which means you can attend a course with a live instructor from anywhere with an internet connection. Our Virtual Classroom training combines our live, virtual cyber range, real-world instructors, content, exercises and peer collaboration to give you the best chance at certification and the biggest return on your investment.</p>
          <p class="subheading secondary--text text-xs-left font-weight-bold">Training includes:</p>
          <ul class="subheading secondary--text text-xs-left">
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Official Courseware
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; iLabs, Online Labs (6 Months Access)
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Test Prep Program (CEH only)
            </li>
          </ul>
        </v-card>
      </v-flex>

      <!-- Private Group -->
      <v-flex xs12 lg6 class="text-xs-center my-5 spread">
        <v-card to="/private-group" class="padding py-4 my-card-2 elevation-12">
          <v-img
            src="https://res.cloudinary.com/missionwebdev/image/upload/f_auto/v1556392353/StealthEntry/eccouncil/private-group.png"
            width="100"
            style="margin: 0 auto;"
          ></v-img>
          <h2 class="display-1 primary--text mt-2 mb-4">Private Group</h2>
          <p
            class="subheading secondary--text text-xs-left"
          >Onsite private courses are a turn-key solution including official courseware, certification exam, and iLabs where applicable. Our team has delivered private courses for companies such as IBM, Dominos, HP, Lockheed Martin and many others. We have also delivered private classes for literally every branch of the US military on and off military installations.</p>
          <p class="subheading secondary--text text-xs-left font-weight-bold">Training includes:</p>
          <ul class="subheading secondary--text text-xs-left">
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Official Courseware
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; iLabs, Online Labs (6 Months Access)
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Certification Exam Voucher
            </li>
            <li>
              <v-icon small class="primary--text">fas fa-check-circle</v-icon>&nbsp; Test Prep Program (CEH only)
            </li>
          </ul>
        </v-card>
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
      video: {
        id: "f2suKC_0UiE"
      }
    };
  }
};
</script>

<style lang="scss" scoped>
/* Mobile Phone Styling */
@media screen and (max-width: 599px) {
  .padding {
    padding-left: 15px !important;
    padding-right: 15px !important;
  }
}
@media screen and (min-width: 600px) {
  .padding {
    padding-left: 50px !important;
    padding-right: 50px !important;
  }
  .spread {
    padding-left: 20px !important;
    padding-right: 20px !important;
  }
}
/* Option Cards */
@media screen and (min-width: 1264px) {
  .my-card {
    height: 750px;
  }
  .my-card-2 {
    height: 565px;
  }
}
@media screen and (min-width: 1500px) {
  .my-card {
    height: 690px;
  }
}
@media screen and (min-width: 2000px) {
  .my-card {
    height: 630px;
  }
  .my-card-2 {
    height: 500px;
  }
}
</style>
