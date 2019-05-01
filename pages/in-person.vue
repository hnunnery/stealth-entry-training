<template>
  <div>
    <CEHinPerson :courseHome="false"/>
    <CNDinPerson :courseHome="false"/>
    <CCISOinPerson :courseHome="false"/>
  </div>
</template>

<script>
import CEHinPerson from "@/components/training/ceh/CEHinPerson";
import CNDinPerson from "@/components/training/cnd/CNDinPerson";
import CCISOinPerson from "@/components/training/cciso/CCISOinPerson";

export default {
  components: {
    CEHinPerson,
    CNDinPerson,
    CCISOinPerson
  }
};
</script>