<template>
  <div>
    <CHFIinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CHFIinPersonPurchase from "@/components/training/chfi/CHFIinPersonPurchase";
import AddOns from "@/components/training/chfi/AddOns";

export default {
  components: {
    CHFIinPersonPurchase,
    AddOns
  }
};
</script>