<template>
  <div>
    <ECSAiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECSAiWeekPurchase from "@/components/training/ecsa/ECSAiWeekPurchase";
import AddOns from "@/components/training/ecsa/AddOns";

export default {
  components: {
    ECSAiWeekPurchase,
    AddOns
  }
};
</script>