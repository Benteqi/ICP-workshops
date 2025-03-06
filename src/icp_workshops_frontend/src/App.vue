<template>
  <div>
    <Icp />
    <Calculator />
  </div>
</template>

<script>
import icp from "./components/icp.vue";
import calculator from "./components/calculator.vue";

export default {
  name: "App",
  components: {
    icp,
    calculator,
  },
};
</script>