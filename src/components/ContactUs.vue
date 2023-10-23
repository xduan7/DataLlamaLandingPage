<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "ContactUs"
});
</script>

<template>
<div class="center lighter-bgc">
  <div class="contact center-row ">
    <div class="card">
      <span class="name green-font">Xiaotian Duan</span>
      <span class="email">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 -1024 1024 1024" width="24"><path d="M160-160q-33 0-56.5-23.5T80-240v-480q0-33 23.5-56.5T160-800h640q33 0 56.5 23.5T880-720v480q0 33-23.5 56.5T800-160H160Zm320-280L160-640v400h640v-400L480-440Zm0-80 320-200H160l320 200ZM160-640v-80 480-400Z"/></svg>
        xduan7@gmail.com
      </span>
      <span class="phone">
        <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 -960 960 960" width="24"><path d="M798-120q-125 0-247-54.5T329-329Q229-429 174.5-551T120-798q0-18 12-30t30-12h162q14 0 25 9.5t13 22.5l26 140q2 16-1 27t-11 19l-97 98q20 37 47.5 71.5T387-386q31 31 65 57.5t72 48.5l94-94q9-9 23.5-13.5T670-390l138 28q14 4 23 14.5t9 23.5v162q0 18-12 30t-30 12ZM241-600l66-66-17-94h-89q5 41 14 81t26 79Zm358 358q39 17 79.5 27t81.5 13v-88l-94-19-67 67ZM241-600Zm358 358Z"/></svg>
        (+1) 518-708-7203
      </span>
      <span class="wechat">
        <svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 21.23 17.09">
      <path d="M21.23,10.83c0-1.47-.67-2.84-1.88-3.87-1.08-.92-2.49-1.45-3.99-1.53-.33-1.51-1.27-2.89-2.64-3.88-1.39-1-3.15-1.55-4.97-1.55C5.7,0,3.77,.68,2.31,1.91,.82,3.17,0,4.86,0,6.66c0,.93,.22,1.83,.65,2.68,.37,.74,.9,1.4,1.55,1.98l-.53,2.96c-.04,.26,.05,.52,.25,.69,.13,.11,.3,.17,.47,.17,.08,0,.17-.01,.25-.04l4.86-1.77c.59-.01,1.15-.05,1.69-.13,.26,.55,.62,1.04,1.07,1.45,1.12,1.02,2.77,1.56,4.91,1.6,.01,0,.02,0,.03,0l3.56,.83c.05,.01,.11,.02,.16,.02,.17,0,.34-.06,.48-.18,.18-.15,.27-.38,.25-.61l-.16-1.71c1.12-1,1.76-2.36,1.76-3.76Zm-13.87,1.08h-.12s-3.97,1.45-3.97,1.45l.37-2.02c.06-.36-.07-.72-.35-.95-1.21-.99-1.87-2.32-1.87-3.72C1.42,3.77,4.26,1.41,7.75,1.41c2.98,0,5.52,1.7,6.18,4.08-1.26,.18-2.43,.69-3.36,1.47-1.21,1.03-1.88,2.4-1.88,3.87,0,.34,.03,.68,.08,.99-.45,.04-.92,.08-1.41,.08Zm10.98,1.79c-.21,.17-.32,.43-.29,.69l.1,1.09-2.63-.61h0c-.11-.03-.21-.04-.32-.04-3.33-.07-5.09-1.45-5.09-4.01,0-2.21,2.18-4.01,4.86-4.01s4.86,1.8,4.86,4.01c0,1.09-.53,2.11-1.49,2.88ZM4.17,5.54c0,.53,.43,.96,.96,.96s.96-.43,.96-.96h0c0-.53-.43-.96-.96-.96s-.96,.43-.96,.96Zm5.09,.1c0,.53,.43,.96,.96,.96s.96-.43,.96-.96-.43-.96-.96-.96-.96,.43-.96,.96h0Zm2.76,4.52c0,.44,.36,.8,.8,.8s.8-.36,.8-.8h0c0-.44-.36-.8-.8-.8s-.8,.36-.8,.8Zm3.59,0c0,.44,.36,.8,.8,.8s.8-.36,.8-.8h0c0-.44-.36-.8-.8-.8s-.8,.36-.8,.8Z"/>
        </svg>
        xduan1207
      </span>
    </div>
    <div class="card">
      <span class="name">Kevin (Gaohong) Wei</span>
      <span class="email">
        <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 -960 960 960" ><path d="M160-160q-33 0-56.5-23.5T80-240v-480q0-33 23.5-56.5T160-800h640q33 0 56.5 23.5T880-720v480q0 33-23.5 56.5T800-160H160Zm320-280L160-640v400h640v-400L480-440Zm0-80 320-200H160l320 200ZM160-640v-80 480-400Z"/></svg>
        gaohongwei@gmail.com
      </span>
      <span class="phone">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 -960 960 960" width="24"><path d="M798-120q-125 0-247-54.5T329-329Q229-429 174.5-551T120-798q0-18 12-30t30-12h162q14 0 25 9.5t13 22.5l26 140q2 16-1 27t-11 19l-97 98q20 37 47.5 71.5T387-386q31 31 65 57.5t72 48.5l94-94q9-9 23.5-13.5T670-390l138 28q14 4 23 14.5t9 23.5v162q0 18-12 30t-30 12ZM241-600l66-66-17-94h-89q5 41 14 81t26 79Zm358 358q39 17 79.5 27t81.5 13v-88l-94-19-67 67ZM241-600Zm358 358Z"/></svg>
        (+1) 510-894-9826
      </span>
      <span class="wechat">
        <svg  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 21.23 17.09">
      <path d="M21.23,10.83c0-1.47-.67-2.84-1.88-3.87-1.08-.92-2.49-1.45-3.99-1.53-.33-1.51-1.27-2.89-2.64-3.88-1.39-1-3.15-1.55-4.97-1.55C5.7,0,3.77,.68,2.31,1.91,.82,3.17,0,4.86,0,6.66c0,.93,.22,1.83,.65,2.68,.37,.74,.9,1.4,1.55,1.98l-.53,2.96c-.04,.26,.05,.52,.25,.69,.13,.11,.3,.17,.47,.17,.08,0,.17-.01,.25-.04l4.86-1.77c.59-.01,1.15-.05,1.69-.13,.26,.55,.62,1.04,1.07,1.45,1.12,1.02,2.77,1.56,4.91,1.6,.01,0,.02,0,.03,0l3.56,.83c.05,.01,.11,.02,.16,.02,.17,0,.34-.06,.48-.18,.18-.15,.27-.38,.25-.61l-.16-1.71c1.12-1,1.76-2.36,1.76-3.76Zm-13.87,1.08h-.12s-3.97,1.45-3.97,1.45l.37-2.02c.06-.36-.07-.72-.35-.95-1.21-.99-1.87-2.32-1.87-3.72C1.42,3.77,4.26,1.41,7.75,1.41c2.98,0,5.52,1.7,6.18,4.08-1.26,.18-2.43,.69-3.36,1.47-1.21,1.03-1.88,2.4-1.88,3.87,0,.34,.03,.68,.08,.99-.45,.04-.92,.08-1.41,.08Zm10.98,1.79c-.21,.17-.32,.43-.29,.69l.1,1.09-2.63-.61h0c-.11-.03-.21-.04-.32-.04-3.33-.07-5.09-1.45-5.09-4.01,0-2.21,2.18-4.01,4.86-4.01s4.86,1.8,4.86,4.01c0,1.09-.53,2.11-1.49,2.88ZM4.17,5.54c0,.53,.43,.96,.96,.96s.96-.43,.96-.96h0c0-.53-.43-.96-.96-.96s-.96,.43-.96,.96Zm5.09,.1c0,.53,.43,.96,.96,.96s.96-.43,.96-.96-.43-.96-.96-.96-.96,.43-.96,.96h0Zm2.76,4.52c0,.44,.36,.8,.8,.8s.8-.36,.8-.8h0c0-.44-.36-.8-.8-.8s-.8,.36-.8,.8Zm3.59,0c0,.44,.36,.8,.8,.8s.8-.36,.8-.8h0c0-.44-.36-.8-.8-.8s-.8,.36-.8,.8Z"/>
        </svg>
        gaohong-wei
      </span>
    </div>
  </div>

  <div class="center">
    <p class="summary">
      At Data Llama, we're poised to redefine the machine learning domain. Our robust strategies and commitment to integrating Large Language Models (LLMs) and Automated Machine Learning (Auto ML) position us at the cutting edge of technological evolution.<br>
      We genuinely believe that with the right partners and a shared vision, the potential for growth is unparalleled. As we seek to expand our horizons and further our impact, your support and collaboration could be pivotal.<br>
      <span class="green-font">We look forward to potential collaboration！</span>
    </p>
  </div>
</div>
</template>

<style scoped>
/* 公用 */
.green-font {
  font-weight: bold;
  color: var(--green-250);
}

.lighter-bgc {
  background-color: var(--gray-150);
}
.center{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.center-row{
  display: flex;
  flex-direction: row;
  align-items: center;
}

.contact{
  display: flex;
  align-items: center;
  width: 90vw;
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
  width: 100%;
  padding: 2rem 0;
  margin: 2rem;
  background-color: var(--gray-125);
  border-radius: 1rem;
  box-shadow: 0 0 5px 0 var(--green-150);
  overflow: hidden;
  white-space: nowrap;
}
span {
  display: flex;
  justify-content: flex-start;
  font-size: 1.25rem;
  font-weight: bold;
  color: var(--gray-600);
}
svg {
  width: 2rem;
  height: 1.5rem;
  margin: 0.5rem;
  fill: var(--green-250);
}

.summary{
  width: 90%;
  font-size: 1.2rem;
  padding: 1rem 2rem;

}
</style>