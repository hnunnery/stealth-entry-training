<template>
  <div>
    <CEHiLearn :courseHome="false"/>
    <CNDiLearn :courseHome="false"/>
  </div>
</template>

<script>
import CEHiLearn from "@/components/training/ceh/CEHiLearn";
import CNDiLearn from "@/components/training/cnd/CNDiLearn";

export default {
  components: {
    CEHiLearn,
    CNDiLearn
  }
};
</script>