<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "ContactUs"
});
</script>

<template>
<div class="contact">
  <div class="card">
    <span class="name green-font">Xiaotian Duan</span>
    <span class="email">
      <svg></svg>
      xduan7@gmail.com
    </span>
    <span class="phone">
      <svg></svg>
      (+1) 518-708-7203
    </span>
    <span class="wechat">
      <svg></svg>
      xduan1207
    </span>
  </div>

  <div class="card">
    <span class="name">Kevin (Gaohong) Wei</span>
    <span class="email">
      <svg></svg>
      gaohongwei@gmail.com
    </span>
    <span class="phone">
      <svg></svg>
      (+1) 510-894-9826
    </span>
    <span class="wechat">
      <svg></svg>
      gaohong-wei
    </span>
  </div>
</div>
</template>

<style scoped>
.contact{
  display: flex;
  align-items: center;
  padding: 2rem;
  overflow: hidden;
}
.name {
  font-size: 2rem;
  font-weight: bold;
  color: var(--green-300);
}

.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 50%;
  padding: 2rem 0;
  margin: 2rem;
  background-color: var(--gray-150);
  border-radius: 1rem;
  box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.2);
}
span {
  display: flex;
  justify-content: flex-start;
  font-size: 1.25rem;
  font-weight: bold;
  color: var(--gray-600);
}
svg {
  width: 1rem;
  height: 1rem;
  margin: 0.5rem;
}
</style>