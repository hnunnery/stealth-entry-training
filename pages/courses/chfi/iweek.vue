<template>
  <div>
    <CHFIiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CHFIiWeekPurchase from "@/components/training/chfi/CHFIiWeekPurchase";
import AddOns from "@/components/training/chfi/AddOns";

export default {
  components: {
    CHFIiWeekPurchase,
    AddOns
  }
};
</script>