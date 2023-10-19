<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "InterfaceFeatures",
});
</script>

<template>
  <div class="root center">
    <img class="interaction" src="../assets/images/chatBox.png"/>
    <img class="interaction" src="../assets/images/output.png"/>
  </div>
</template>

<style scoped>
/* 公用 */
.green-font {
  font-weight: bold;
  color: var(--green-250);
}
/* 流程图部分 */
.center{
  display: flex;
  flex-direction: column;
  align-items: center;
}

.interaction {
  width: 90%;
  padding: 2rem;
}
</style>