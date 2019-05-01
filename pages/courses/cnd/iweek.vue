<template>
  <div>
    <CEHiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CEHiWeekPurchase from "@/components/training/ceh/CEHiWeekPurchase";
import AddOns from "@/components/training/ceh/AddOns";

export default {
  components: {
    CEHiWeekPurchase,
    AddOns
  }
};
</script>