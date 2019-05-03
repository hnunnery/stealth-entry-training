<template>
  <div>
    <CHFIinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CHFIinPersonPurchase from "@/components/training/CHFI/CHFIinPersonPurchase";
import AddOns from "@/components/training/CHFI/AddOns";

export default {
  components: {
    CHFIinPersonPurchase,
    AddOns
  }
};
</script>