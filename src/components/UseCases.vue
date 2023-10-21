<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "UseCases",
});
</script>

<template>
  <div class="center lighter-bgc">
    <img class="use-cases-img" src="../assets/images/InterfaceFeatures/example00.png" alt="example">
    <img class="use-cases-img" src="../assets/images/InterfaceFeatures/example01.png" alt="example">
    <img class="use-cases-img" src="../assets/images/InterfaceFeatures/example02.png" alt="example">
    <img class="use-cases-img" src="../assets/images/InterfaceFeatures/example03.png" alt="example">
    <img class="use-cases-img" src="../assets/images/InterfaceFeatures/example04.png" alt="example">
  </div>
</template>

<style scoped>
/* 公用 */
.green-font {
  font-weight: bold;
  color: var(--green-250);
}
.gray-font {
  font-weight: bold;
  color: var(--gray-600);
}
.lighter-bgc {
  background-color: var(--gray-150);
}

.center{
  display: flex;
  flex-direction: column;
  align-items: center;
}

.use-cases-img {
  width: 80%;
  padding: 3rem 2rem 2rem 2rem;
}
</style>