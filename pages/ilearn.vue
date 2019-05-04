<template>
  <div>
    <CEHiLearn :courseHome="false"/>
    <CNDiLearn :courseHome="false"/>
    <CCISOiLearn :courseHome="false"/>
    <CTIAiLearn :courseHome="false"/>
    <CHFIiLearn :courseHome="false"/>
    <ECSAiLearn :courseHome="false"/>
    <ECIHiLearn :courseHome="false"/>
    <EDRPiLearn :courseHome="false"/>
    <CCiLearn :courseHome="false"/>
  </div>
</template>

<script>
import CEHiLearn from "@/components/training/ceh/CEHiLearn";
import CNDiLearn from "@/components/training/cnd/CNDiLearn";
import CCISOiLearn from "@/components/training/cciso/CCISOiLearn";
import CTIAiLearn from "@/components/training/ctia/CTIAiLearn";
import CHFIiLearn from "@/components/training/chfi/CHFIiLearn";
import ECSAiLearn from "@/components/training/ecsa/ECSAiLearn";
import ECIHiLearn from "@/components/training/ecih/ECIHiLearn";
import EDRPiLearn from "@/components/training/edrp/EDRPiLearn";
import CCiLearn from "@/components/training/cc/CCiLearn";

export default {
  components: {
    CEHiLearn,
    CNDiLearn,
    CCISOiLearn,
    CTIAiLearn,
    CHFIiLearn,
    ECSAiLearn,
    ECIHiLearn,
    EDRPiLearn,
    CCiLearn
  }
};
</script>