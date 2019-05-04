<template>
  <div>
    <CEHiWeek :courseHome="false"/>
    <CNDiWeek :courseHome="false"/>
    <CCISOiWeek :courseHome="false"/>
    <CTIAiWeek :courseHome="false"/>
    <CHFIiWeek :courseHome="false"/>
    <ECSAiWeek :courseHome="false"/>
  </div>
</template>

<script>
import CEHiWeek from "@/components/training/ceh/CEHiWeek";
import CNDiWeek from "@/components/training/cnd/CNDiWeek";
import CCISOiWeek from "@/components/training/cciso/CCISOiWeek";
import CTIAiWeek from "@/components/training/ctia/CTIAiWeek";
import CHFIiWeek from "@/components/training/chfi/CHFIiWeek";
import ECSAiWeek from "@/components/training/ecsa/ECSAiWeek";

export default {
  components: {
    CEHiWeek,
    CNDiWeek,
    CCISOiWeek,
    CTIAiWeek,
    CHFIiWeek,
    ECSAiWeek
  }
};
</script>