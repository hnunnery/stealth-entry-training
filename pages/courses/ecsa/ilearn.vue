<template>
  <div>
    <ECSAiLearnPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECSAiLearnPurchase from "@/components/training/ecsa/ECSAiLearnPurchase";
import AddOns from "@/components/training/ecsa/AddOns";

export default {
  components: {
    ECSAiLearnPurchase,
    AddOns
  }
};
</script>