<template>
  <div>
    <CEHinPerson :courseHome="false"/>
    <CNDinPerson :courseHome="false"/>
    <CCISOinPerson :courseHome="false"/>
    <CHFIinPerson :courseHome="false"/>
    <ECSAinPerson :courseHome="false"/>
  </div>
</template>

<script>
import CEHinPerson from "@/components/training/ceh/CEHinPerson";
import CNDinPerson from "@/components/training/cnd/CNDinPerson";
import CCISOinPerson from "@/components/training/cciso/CCISOinPerson";
import CHFIinPerson from "@/components/training/chfi/CHFIinPerson";
import ECSAinPerson from "@/components/training/ecsa/ECSAinPerson";

export default {
  components: {
    CEHinPerson,
    CNDinPerson,
    CCISOinPerson,
    CHFIinPerson,
    ECSAinPerson
  }
};
</script>