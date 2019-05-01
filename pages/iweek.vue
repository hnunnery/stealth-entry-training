<template>
  <div>
    <CEHiWeek :courseHome="false"/>
    <CNDiWeek :courseHome="false"/>
    <CCISOiWeek :courseHome="false"/>
  </div>
</template>

<script>
import CEHiWeek from "@/components/training/ceh/CEHiWeek";
import CNDiWeek from "@/components/training/cnd/CNDiWeek";
import CCISOiWeek from "@/components/training/cciso/CCISOiWeek";

export default {
  components: {
    CEHiWeek,
    CNDiWeek,
    CCISOiWeek
  }
};
</script>