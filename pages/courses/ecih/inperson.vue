<template>
  <div>
    <ECIHinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import ECIHinPersonPurchase from "@/components/training/ecih/ECIHinPersonPurchase";
import AddOns from "@/components/training/ecih/AddOns";

export default {
  components: {
    ECIHinPersonPurchase,
    AddOns
  }
};
</script>