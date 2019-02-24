<template>
  <div id="app">
    <VsdHeader title="Vue San Diego" />

    <router-view />

    <VsdFooter />
  </div>
</template>

<script>
import VsdHeader from "@/components/root/Header";
import VsdFooter from "@/components/root/Footer";

export default {
  components: {
    VsdHeader,
    VsdFooter
  }
};
</script>
