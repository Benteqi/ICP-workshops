<template>
  <div class="container mx-auto flex flex-col gap-8 justify-center items-center">
    <Icp />
    <Calculator />
  </div>
</template>

<script>
import Icp from "./components/Icp.vue";
import Calculator from "./components/Calculator.vue";

export default {
  name: "App",
  components: {
    Icp,
    Calculator,
  },
};
</script>