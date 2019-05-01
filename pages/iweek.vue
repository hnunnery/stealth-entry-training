<template>
  <div>
    <CEHiWeek :courseHome="false"/>
    <CNDiWeek :courseHome="false"/>
  </div>
</template>

<script>
import CEHiWeek from "@/components/training/ceh/CEHiWeek";
import CNDiWeek from "@/components/training/cnd/CNDiWeek";

export default {
  components: {
    CEHiWeek,
    CNDiWeek
  }
};
</script>