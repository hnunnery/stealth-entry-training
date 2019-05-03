<template>
  <div>
    <ECSAiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECSAiWeekPurchase from "@/components/training/ECSA/ECSAiWeekPurchase";
import AddOns from "@/components/training/ECSA/AddOns";

export default {
  components: {
    ECSAiWeekPurchase,
    AddOns
  }
};
</script>