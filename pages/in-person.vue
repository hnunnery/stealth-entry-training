<template>
  <div>
    <CEHinPerson :courseHome="false"/>
    <CNDinPerson :courseHome="false"/>
  </div>
</template>

<script>
import CEHinPerson from "@/components/training/ceh/CEHinPerson";
import CNDinPerson from "@/components/training/cnd/CNDinPerson";

export default {
  components: {
    CEHinPerson,
    CNDinPerson
  }
};
</script>