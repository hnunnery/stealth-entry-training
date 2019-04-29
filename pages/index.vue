<template>
  <div>
    <TrainingOptions/>
    <Courses/>
  </div>
</template>

<script>
import Courses from "@/components/training/Courses";
import TrainingOptions from "@/components/training/TrainingOptions";

export default {
  name: "index",
  components: {
    Courses,
    TrainingOptions
  }
};
</script>