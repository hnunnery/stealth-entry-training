<template>
  <div>
    <ECIHiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECIHiWeekPurchase from "@/components/training/ECIH/ECIHiWeekPurchase";
import AddOns from "@/components/training/ECIH/AddOns";

export default {
  components: {
    ECIHiWeekPurchase,
    AddOns
  }
};
</script>