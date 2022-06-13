<template>
  <div class="neural-network-background-container" v-bind:class="rootClassName">
    <iframe
      src="https://giphy.com/embed/5owNSuvkqgLg1iqNrF"
      class="neural-network-background-iframe"
    ></iframe>
  </div>
</template>

<script>
export default {
  name: 'NeuralNetworkBackground',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.neural-network-background-container {
  width: 100%;
  height: 400px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.neural-network-background-iframe {
  width: 100%;
  height: 100%;
}
</style>
