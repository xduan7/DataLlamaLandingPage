<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "InterfaceFeatures",
});
</script>

<template>
  <div class="root center">
    <div class="lighter-bgc center">
      <img class="interaction-img" src="../assets/images/interface/chatBox.png" alt="chatBox">
      <img class="interaction-img" src="../assets/images/interface/output.png" alt="output">
    </div>

    <div class="center">
      <h1 class="gray-font center">Function Display Screenshots</h1>
      <img class="screenshot-img" src="../assets/images/interface/txt.gif" alt="txt">
      <p class=" screenshot-p">
        <span class="green-font">Data Llama actively demonstrates its understanding of the current data,</span>
        updating users in real-time about ongoing tasks, keeping them informed at every step.
        <span class="green-font">By intelligently anticipating user needs, Data Llama streamlines processes, resulting in a more intuitive and simplified user experience.</span>
        Moreover, it seeks additional information from the users when necessary, guaranteeing perfect alignment with user intentions.
      </p>
    </div>
    <div class="center">
      <img class="screenshot-img" src="../assets/images/interface/options.gif" alt="options">
      <p class="screenshot-p">
        <span class="green-font">At every decision point, Data Llama offers users a clear set of choices.</span>
        When users are unsure, they can select the 'I don't know' option, and Data Llama takes the lead by suggesting a data-driven course of action that aligns with user preferences.
        <span class="green-font">Alternatively, users can input their choice directly if none of the options fit.</span>
        This ensures that our users always remain in full charge while benefiting from Data Llama's assistance.
      </p>
    </div>
    <div class="center">
      <img class="screenshot-img" src="../assets/images/interface/explanation.png" alt="explanation">
      <p class="screenshot-p">
        Data Llama acts like your personal assistant in the world of data science. When you encounter complex terms or concepts,
        <span class="green-font">a simple hover prompts Data Llama to provide clear explanations.</span>
        And if you need deeper insights, you can directly ask Data Llama for guidance on the intricate details of machine learning experiments. Our user-friendly dialogue interface ensures that navigating our platform is a breeze, making data science accessible to all.
      </p>
    </div>
    <div class="center">
      <img class="screenshot-img" src="../assets/images/interface/bubbleDiagram.gif" alt="bubbleDiagram">
      <p class="screenshot-p">
        <span class="green-font">Data Llama transforms your data into interactive plots,</span>
        acting like a magnifying glass for your data. These visualizations not only allow you to see your data but also uncover hidden insights effortlessly. With simple interactions like hovering, selecting, and zooming, you have the power to dive deep into your data's meaning, making data exploration a breeze.
      </p>
    </div>
    <div class="center">
      <img class="screenshot-img" src="../assets/images/interface/searching.png" alt="searching">
      <p class="screenshot-p">
        When confronted with unfamiliar data, like biomedical information,
        <span class="green-font">Data Llama takes a proactive approach by searching online for relevant information.</span>
        This dynamic adaptation enhances the quality of data analysis by applying domain-specific knowledge, ultimately providing more valuable insights to users.
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
/* 交互部分 */
.interaction-img {
  width: 90%;
  padding: 2rem;
}
.screenshot-img {
  width: 75%;
  padding: 3rem 2rem 2rem 2rem;
}

h1 {
  font-size: 3rem;
  margin: 2rem;
}

.screenshot-p{
  width:80%;
  font-size: 1.2rem;
  padding: 1rem 2rem;
  background-color: var(--gray-125);
  border-radius: 1rem;
}

</style>