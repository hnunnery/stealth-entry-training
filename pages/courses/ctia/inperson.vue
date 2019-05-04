<template>
  <div>
    <CTIAinPersonPurchase/>
    <AddOns/>
  </div>
</template>

<script>
import CTIAinPersonPurchase from "@/components/training/ctia/CTIAinPersonPurchase";
import AddOns from "@/components/training/ctia/AddOns";

export default {
  components: {
    CTIAinPersonPurchase,
    AddOns
  }
};
</script>