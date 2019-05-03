<template>
  <div>
    <CEHiLearn :courseHome="false"/>
    <CNDiLearn :courseHome="false"/>
    <CCISOiLearn :courseHome="false"/>
    <CHFIiLearn :courseHome="false"/>
    <ECSAiLearn :courseHome="false"/>
    <ECIHiLearn :courseHome="false"/>
  </div>
</template>

<script>
import CEHiLearn from "@/components/training/ceh/CEHiLearn";
import CNDiLearn from "@/components/training/cnd/CNDiLearn";
import CCISOiLearn from "@/components/training/cciso/CCISOiLearn";
import CHFIiLearn from "@/components/training/chfi/CHFIiLearn";
import ECSAiLearn from "@/components/training/ecsa/ECSAiLearn";
import ECIHiLearn from "@/components/training/ecih/ECIHiLearn";

export default {
  components: {
    CEHiLearn,
    CNDiLearn,
    CCISOiLearn,
    CHFIiLearn,
    ECSAiLearn,
    ECIHiLearn
  }
};
</script>