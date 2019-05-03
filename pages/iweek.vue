<template>
  <div>
    <CEHiWeek :courseHome="false"/>
    <CNDiWeek :courseHome="false"/>
    <CCISOiWeek :courseHome="false"/>
    <CHFIiWeek :courseHome="false"/>
    <ECSAiWeek :courseHome="false"/>
    <ECIHiWeek :courseHome="false"/>
  </div>
</template>

<script>
import CEHiWeek from "@/components/training/ceh/CEHiWeek";
import CNDiWeek from "@/components/training/cnd/CNDiWeek";
import CCISOiWeek from "@/components/training/cciso/CCISOiWeek";
import CHFIiWeek from "@/components/training/chfi/CHFIiWeek";
import ECSAiWeek from "@/components/training/ecsa/ECSAiWeek";
import ECIHiWeek from "@/components/training/ecih/ECIHiWeek";

export default {
  components: {
    CEHiWeek,
    CNDiWeek,
    CCISOiWeek,
    CHFIiWeek,
    ECSAiWeek,
    ECIHiWeek
  }
};
</script>