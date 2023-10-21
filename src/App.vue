<script setup>
import LandingHeader from '@/components/LandingHeader.vue';
import HeroBanner from '@/components/HeroBanner.vue';
import SwitchPages from '@/views/SwitchPages.vue';
import landingFooter from '@/components/LandingFooter.vue';
</script>

<template>
  <LandingHeader />
  <HeroBanner />
  <SwitchPages />
  <landingFooter />
</template>

<style>
body {
  height: auto;
  margin: 0;
  padding: 0;
  overflow-y: auto;
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  /* 设置Firefox滚动条 */
  scrollbar-width: thin; /* 或 'auto' 或 'none' 或 'thin' */
  scrollbar-color: var(--green-200) var(--gray-300); /* 滚动条颜色 轨道颜色 */

}

html {
  font-family: Arial, sans-serif;
  line-height: 2;
  background-color: var(--gray-200);
}

:root {
  --dynamic-sidebar-width: min(max(18vw, 250px), 300px);
  --gray-50: #f9f8fb;
  --gray-100: #eeecf5;
  --gray-125: #e2e0eb;
  --gray-150: #d5d3df;
  --gray-200: #cbc9d6;
  --gray-300: #a19daf;
  --gray-400: #716c82;
  --gray-500: #5a5666;
  --gray-600: #2d2a34;
  --gray-700: #201d25;
  --green-25: #a4cad4;
  --green-50: #86d7d9;
  --green-100: #6cc9ca;
  --green-150: #6cb5b8;
  --green-200: #3f9096;
  --green-250: #2d8c93;
  --green-300: #356c71;
}

/* 设置Chrome&Safari滚动条 */
::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  background: var(--gray-300); /* 轨道的背景色 */
}

::-webkit-scrollbar-thumb {
  background: var(--green-200); /* 滑块的背景色 */
  border-radius: 5px; /* 滑块的圆角大小 */
}

::-webkit-scrollbar-thumb:hover {
  background: var(--green-300); /* 滑块鼠标悬停时的颜色 */
}
</style>
