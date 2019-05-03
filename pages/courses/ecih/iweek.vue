<template>
  <div>
    <ECIHiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECIHiWeekPurchase from "@/components/training/ecih/ECIHiWeekPurchase";
import AddOns from "@/components/training/ecih/AddOns";

export default {
  components: {
    ECIHiWeekPurchase,
    AddOns
  }
};
</script>