<template>
  <div>
    <ECSAinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECSAinPersonPurchase from "@/components/training/ecsa/ECSAinPersonPurchase";
import AddOns from "@/components/training/ecsa/AddOns";

export default {
  components: {
    ECSAinPersonPurchase,
    AddOns
  }
};
</script>