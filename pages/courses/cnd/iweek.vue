<template>
  <div>
    <CNDiWeekPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CNDiWeekPurchase from "@/components/training/cnd/CNDiWeekPurchase";
import AddOns from "@/components/training/cnd/AddOns";

export default {
  components: {
    CNDiWeekPurchase,
    AddOns
  }
};
</script>