<template>
  <div>
    <ECSAinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECSAinPersonPurchase from "@/components/training/ECSA/ECSAinPersonPurchase";
import AddOns from "@/components/training/ECSA/AddOns";

export default {
  components: {
    ECSAinPersonPurchase,
    AddOns
  }
};
</script>