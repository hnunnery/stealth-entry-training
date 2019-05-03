<template>
  <div>
    <ECIHinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECIHinPersonPurchase from "@/components/training/ECIH/ECIHinPersonPurchase";
import AddOns from "@/components/training/ECIH/AddOns";

export default {
  components: {
    ECIHinPersonPurchase,
    AddOns
  }
};
</script>