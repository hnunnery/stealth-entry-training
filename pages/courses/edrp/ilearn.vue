<template>
  <div>
    <EDRPiLearnPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import EDRPiLearnPurchase from "@/components/training/edrp/EDRPiLearnPurchase";
import AddOns from "@/components/training/edrp/AddOns";

export default {
  components: {
    EDRPiLearnPurchase,
    AddOns
  }
};
</script>