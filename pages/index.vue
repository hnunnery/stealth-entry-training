<template>
  <div>
    <Courses/>
    <TrainingOptions/>
  </div>
</template>

<script>
import Courses from "@/components/Courses";
import TrainingOptions from "@/components/TrainingOptions";

export default {
  name: "index",
  components: {
    Courses,
    TrainingOptions
  }
};
</script>