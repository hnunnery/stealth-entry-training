<template>
  <div>
    <CEHinPerson :courseHome="false"/>
    <CNDinPerson :courseHome="false"/>
    <CCISOinPerson :courseHome="false"/>
    <CHFIinPerson :courseHome="false"/>
    <ECSAinPerson :courseHome="false"/>
    <ECIHinPerson :courseHome="false"/>
  </div>
</template>

<script>
import CEHinPerson from "@/components/training/ceh/CEHinPerson";
import CNDinPerson from "@/components/training/cnd/CNDinPerson";
import CCISOinPerson from "@/components/training/cciso/CCISOinPerson";
import CHFIinPerson from "@/components/training/CHFI/CHFIinPerson";
import ECSAinPerson from "@/components/training/ECSA/ECSAinPerson";
import ECIHinPerson from "@/components/training/ECIH/ECIHinPerson";

export default {
  components: {
    CEHinPerson,
    CNDinPerson,
    CCISOinPerson,
    CHFIinPerson,
    ECSAinPerson,
    ECIHinPerson
  }
};
</script>