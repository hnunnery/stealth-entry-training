<template>
  <div>
    <CHFIiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CHFIiWeekPurchase from "@/components/training/CHFI/CHFIiWeekPurchase";
import AddOns from "@/components/training/CHFI/AddOns";

export default {
  components: {
    CHFIiWeekPurchase,
    AddOns
  }
};
</script>