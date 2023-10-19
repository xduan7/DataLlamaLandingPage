<script setup>
import { defineOptions} from "vue";
// import { useRouter } from 'vue-router';

defineOptions({
  name: "HeroBanner",
});

// const router = useRouter();
// const goToChatDataLlama = () => {
//   router.push("/chat");
// }
</script>

<template>
  <div class="banner">
    <img class="background-image" src="../assets/images/wall_paper.jpg" />
    <div class="title">
      <!-- <h1 class="name">Data Llama</h1> -->
      <svg class="name" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 693.66 146.23">
        <g>
          <path d="M0,144.48L19.61,5.5h24.6c35.26,0,43.86,27.69,38.18,71.04-5.16,41.62-21.33,67.94-55.56,67.94H0ZM35.09,21.16l-15.14,107.5h8.94c19.61,0,30.27-18.4,34.92-51.6,5.5-38.35-1.55-55.38-21.5-55.73l-7.22-.17Z"/>
          <path d="M131.41,144.48l.86-9.46c-5.16,6.88-11.52,11.18-18.4,11.18-16.51,0-27.52-14.96-21.67-56.76,4.82-34.92,18.58-51.43,35.26-51.43,7.57,0,13.24,3.61,16.68,10.49l1.2-8.94h16.68l-14.79,104.92h-15.82Zm-13.07-13.76c8.43,0,14.28-10.32,17.03-20.98l5.5-38.36c.17-10.49-4.13-17.89-11.87-17.89-10.84,0-17.03,17.2-19.78,37.84-2.92,22.19-2.75,39.39,9.12,39.39Z"/>
          <path d="M179.56,54.7h-11.18l2.24-15.14h11.35l4.47-28.9h15.82l-4.3,28.9h19.44l-2.24,15.14h-19.61l-8.6,57.45c-1.89,12.56-.52,18.58,6.02,18.58,2.75,0,5.85-1.2,8.77-3.27l5.33,14.1c-17.72,8.26-42.48,9.12-36.81-27.52l9.29-59.34Z"/>
          <path d="M255.24,144.48l.86-9.46c-5.16,6.88-11.52,11.18-18.4,11.18-16.51,0-27.52-14.96-21.67-56.76,4.82-34.92,18.58-51.43,35.26-51.43,7.57,0,13.24,3.61,16.68,10.49l1.2-8.94h16.68l-14.79,104.92h-15.82Zm-13.07-13.76c8.43,0,14.28-10.32,17.03-20.98l5.5-38.36c.17-10.49-4.13-17.89-11.87-17.89-10.84,0-17.03,17.2-19.78,37.84-2.92,22.19-2.75,39.39,9.12,39.39Z"/>
          <path d="M379.6,144.48h-57.62L341.41,5.5h17.2l-17.2,122.63h40.42l-2.24,16.34Z"/>
          <path d="M391.12,144.48L411.59,0h16.68l-20.47,144.48h-16.68Z"/>
          <path d="M468.69,144.48l.86-9.46c-5.16,6.88-11.52,11.18-18.4,11.18-16.51,0-27.52-14.96-21.67-56.76,4.82-34.92,18.58-51.43,35.26-51.43,7.57,0,13.24,3.61,16.68,10.49l1.2-8.94h16.68l-14.79,104.92h-15.82Zm-13.07-13.76c8.43,0,14.28-10.32,17.03-20.98l5.5-38.36c.17-10.49-4.13-17.89-11.87-17.89-10.84,0-17.03,17.2-19.78,37.84-2.92,22.19-2.75,39.39,9.12,39.39Z"/>
          <path d="M501.71,144.48l14.96-104.92h15.65l-.86,10.15c5.68-8.6,13.07-11.87,19.78-11.87,9.12,0,16.86,4.3,18.92,15.82,6.02-11.52,14.45-15.82,22.19-15.82,12.38,0,22.19,8.08,18.92,30.96l-10.66,75.68h-16.86l10.49-72.93c1.72-12.04-1.2-18.23-8.77-18.23s-13.42,7.91-15.82,19.09l-10.15,72.07h-16.86l10.49-72.93c1.72-12.04-1.2-18.23-8.77-18.23s-13.07,7.57-15.65,18.4l-10.32,72.75h-16.68Z"/>
          <path d="M663.05,144.48l.86-9.46c-5.16,6.88-11.52,11.18-18.4,11.18-16.51,0-27.52-14.96-21.67-56.76,4.82-34.92,18.58-51.43,35.26-51.43,7.57,0,13.24,3.61,16.68,10.49l1.2-8.94h16.68l-14.79,104.92h-15.82Zm-13.07-13.76c8.43,0,14.28-10.32,17.03-20.98l5.5-38.36c.17-10.49-4.13-17.89-11.87-17.89-10.84,0-17.03,17.2-19.78,37.84-2.92,22.19-2.75,39.39,9.12,39.39Z"/>
        </g>
      </svg>
      <h2 class="slogan">Unleash the Power of Data</h2>
      <button class="toChatBtn" >
        Coming Soon
        <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24">
          <path d="M120-160v-640l760 320-760 320Zm80-120 474-200-474-200v140l240 60-240 60v140Zm0 0v-400 400Z"/>
        </svg>
      </button>
    </div>
  </div>
</template>

<style scoped>
.banner {
  display: flex;
  justify-content: center;
  align-content: center;
  height: 100vh;
  overflow: hidden;
}
.background-image {

  width: 100%;
  height: 100vh;
  opacity: 0.6;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.title {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 31vh;
  line-height: 1;
  white-space: nowrap;
}
.name {
  width: 800px;
  margin-block: 1rem;
  margin-right: 20px;
  padding-bottom: 0.5rem;
  border-bottom: 0.5rem solid var(--gray-700);
}
.slogan {
  font-size: 3.75rem;
  color: var(--gray-700);
  margin-block: 0.75rem;
  margin-right: 12px;
}
.toChatBtn {
  display: flex;
  align-items: center;
  font-size: 2rem;
  font-weight: bold;
  padding: 1rem 1.5rem;
  margin: 10px 25px 0 0;
  border-radius: 0.5rem;
  color: var(--gray-50);
  background-color: var(--green-200);
  border: none;
  border-color: var(--green-150);
  outline: none;
  cursor: pointer;
}
.toChatBtn:hover {
  background-color: var(--green-300);
  box-shadow: 0 0 8px var(--gray-100);
}
.toChatBtn svg{
  margin-left: 0.5rem;
  width: 2rem;
  height: 2rem;
  fill: var(--gray-50);
}
</style>