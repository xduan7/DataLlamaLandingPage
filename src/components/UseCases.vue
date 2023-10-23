<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "UseCases",
});
</script>

<template>
  <div class="center lighter-bgc">
    <img class="use-cases-img" src="../assets/images/interface/example00.png" alt="example">
    <img class="use-cases-img" src="../assets/images/interface/example01.png" alt="example">
    <p class="description">
      Retailers often struggle with figuring out what they‘ll need in stock, especially when their data is scattered all over the place. That’s where Data Llama comes in.
      <span class="green-font">It acts as a bridge, seamlessly connecting these data islands.</span>
      By extracting insights from historical records, our solution simplifies warehouse planning, cuts costs, and optimizes inventory management. It‘s more than just forecasting; it’s about transforming the entire process, from data collection and cleaning all the way to prediction.
    </p>
    <img class="use-cases-img" src="../assets/images/interface/example02_en.png" alt="example">
    <p class="description">
      Traditional Auto ML platforms often stumble when it comes to tasks like these, due to the lack of a clear predictive target and the challenge posed by multimodal analysis. Data Llama stands out. Our system delves into historical reports,
      <span class="green-font">effectively combining textual insights with outlier detection on tabular data.</span>
      This holistic approach enables us to spot financial inconsistencies, like anomalies in expenditure patterns, helping businesses steer clear of latent risks and potential losses.
    </p>
    <img class="use-cases-img" src="../assets/images/interface/example03.png" alt="example">
    <p class="description">
      Market research requires a broader perspective, a need well addressed by Data Llama.
      <span class="green-font">Our platform seamlessly blends the abundance of online information with your local data, creating organized, actionable insights.</span>
      This synthesis unveils a broader market view, highlighting potential growth opportunities.
      <span class="green-font">Our tools translate these insights into interactive plots,</span>
      rendering the analysis easily digestible and simplifying data-driven decision-making.
    </p>
    <img class="use-cases-img" src="../assets/images/interface/example04.png" alt="example">
    <p class="description">
      In sectors like healthcare, where every insight could be a step towards saving lives, understanding data is crucial. Unlike other Auto ML platforms, Data Llama goes beyond mere predictions.
      <span class="green-font">Powered by advanced LLMs, it provides thorough explanations during analysis,</span>
      providing a deeper insights that guides action. This enables healthcare professionals to not only predict outcomes but understand the underlying factors, leading to better health advice and research directions.
    </p>
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

.use-cases-img {
  width: 80%;
  padding: 3rem 2rem 2rem 2rem;
}

.description {
  width: 80%;
  font-size: 1.2rem;
  padding: 1rem 2rem 2rem 2rem;
}
</style>