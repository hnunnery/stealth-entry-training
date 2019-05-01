<template>
  <div>
    <CNDinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CNDinPersonPurchase from "@/components/training/cnd/CNDinPersonPurchase";
import AddOns from "@/components/training/cnd/AddOns";

export default {
  components: {
    CNDinPersonPurchase,
    AddOns
  }
};
</script>