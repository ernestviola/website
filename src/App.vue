<template>
  <div id="app">
    <vsd-header title="Vue San Diego"/>

    <router-view />

    <!-- Footer -->
    <VsdFooter />
  </div>
</template>

<script>
import VsdHeader from '@/components/root/Header'
import VsdFooter from '@/components/root/Footer'

export default {
  components: {
    VsdHeader,
    VsdFooter
  }
}
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
