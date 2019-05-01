<template>
  <div>
    <CEHiLearn :courseHome="false"/>
    <CNDiLearn :courseHome="false"/>
    <CCISOiLearn :courseHome="false"/>
  </div>
</template>

<script>
import CEHiLearn from "@/components/training/ceh/CEHiLearn";
import CNDiLearn from "@/components/training/cnd/CNDiLearn";
import CCISOiLearn from "@/components/training/cciso/CCISOiLearn";

export default {
  components: {
    CEHiLearn,
    CNDiLearn,
    CCISOiLearn
  }
};
</script>