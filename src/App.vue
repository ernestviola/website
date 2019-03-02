<template>
  <div class="vsd-root">
    <VsdHeader title="Vue San Diego" />

    <router-view class="vsd-content" />

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
  },

  errorCaptured(error, component, info) {
    console.log("An error occured:\n", error, component, info);
  }
};
</script>

<style lang="scss">
.vsd-root {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.vsd-content {
  flex-grow: 1;
}
</style>
