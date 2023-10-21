<script setup>
import { defineOptions} from "vue";

defineOptions({
  name: "TeamOverview",
});
</script>

<template>
<div class="center lighter-bgc ">
<!--  core team members-->
  <h1 class="center">Team & Partners </h1>
  <p>
    Our team, led by a software architect with 20 years of experience and a Ph.D. candidate specializing in machine learning,
    <span class="green-font ">seamlessly blends advanced research with solid development. </span>
    Advised by two professors and a Harvard postdoc, we work closely together to ensure the excellence of Data Llama.
  </p>
  <div class=" core center-row">
    <div class="card center light-bgc">
      <span class="position">CEO</span>
      <span class="name green-font">Kevin Wei</span>
      <span class="occupation green-font">Software Architect</span>
      <span class="experiment">
        20 years of software<br>
         development experience;<br>
        Employed at Dell, Palo Alto <br>
        and several other startups<br>
      </span>
      <span class="achievement">Holds 2 U.S. patents</span>
    </div>

    <div class="card center dark-bgc">
      <span class="position">CTO</span>
      <span class="name green-font">Xiaotian Duan</span>
      <span class="occupation green-font">UChicago Ph.D. Student</span>
      <span class="experiment">
        Computer Vision<br>
        Continuous Learning<br>
        Machine Learning Applications<br>
      </span>
      <span class="achievement">
        4 Publications<br>
        Multi world champions in <br>
        machine learning competitions<br>
      </span>
    </div>

    <div class="card center light-bgc">
      <span class="position">Chief Engineer</span>
      <span class="name green-font">Yang Yang</span>
      <span class="occupation green-font">Product Manager</span>
      <span class="experiment">
        Tech Lead<br>
        8 years of software <br>
        development experience<br>
      </span>
      <span class="achievement">
        Engaged in mobile games that <br>
        generated 10M revenue and <br>
        software with 1M+ users<br>
      </span>
    </div>
  </div>
    <div class="core-team-title center">Core Team Members</div>

  <div class="ads-partner center-row">
  <!--  advisors-->
    <div class="advisors center">
      <div class="advisors-card">
        <div class="card center dark-bgc">
          <span class="name green-font">Yong Liu</span>
          <span class="occupation green-font">
            University of Aizu<br>
            Japan<br>
            Professor<br>
          </span>
          <span class="experiment">
            Applied Mathematics <br>
            Artificial Intelligence<br>
          </span>
        </div>

        <div class="card center light-bgc">
          <span class="name green-font">Qiuxin Wu</span>
          <span class="occupation green-font">
            BISTU, China<br>
            Professor<br>
          </span>
          <span class="experiment">
            Big Data<br>
            Artificial Intelligence<br>
          </span>
        </div>

        <div class="card center dark-bgc">
          <span class="name green-font">Dongfang Xu</span>
          <span class="occupation green-font">
          Harvard University<br>
          Postdoc<br>
        </span>
          <span class="experiment">
        Natural Language <br>
          Processing<br>
        </span>
        </div>
      </div>
      <div class="advisors-title center">Advisors</div>
    </div>

  <!--  partners-->
    <div class="partners center">
      <div class="partners-logo"></div>
      <div class="key-partner-title center">Key Partner</div>
    </div>
  </div>
</div>
</template>

<style scoped>
/* 公用 */
.green-font {
  font-weight: bold;
  color: var(--green-300);
}
.gray-font {
  font-weight: bold;
  color: var(--gray-600);
}
.lighter-bgc {
  background-color: var(--gray-150);
}
.light-bgc {
  background-color: var(--gray-175);
}
.dark-bgc {
  background-color: var(--gray-200);
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
h1{
  font-size: 3rem;
  margin: 2rem 0 0 0;
}
p {
  width: 80%;
  font-size: 1.2rem;
  padding: 1rem 2rem 2rem 2rem;
}
/* team */
.core{
  width: 100%;
  overflow: clip;
}
.core .card {
  width: 35%;
  height: 30rem;
  padding: 0;
  overflow: clip;
}

.position {
  font-size: 1.25rem;
  font-weight: bold;
  padding: 0.1rem 1rem;
  color: var(--gray-50);
  background-color: var(--green-200);
}
.name {
  font-size: 2rem;
  font-weight: bold;
  padding: 0.1rem 1rem;
  text-align: center;
}
.occupation {
  font-size: 1.25rem;
  font-weight: bold;
  padding: 0.1rem 1rem;
  text-align: center;
  line-height: 1.5;
}
.experiment,.achievement{
  font-size: 1rem;
  padding: 1.5rem;
  text-align: center;
}
.core-team-title {
  width: 100%;
  font-size: 1.25rem;
  font-weight: bold;
  padding: 0.1rem;
  color: var(--gray-50);
  background-color: var(--green-200);
}
/* advisors & partner */
.ads-partner{
  width: 100%;
  overflow: clip;
}
.advisors-title {
  width: 100%;
  font-size: 1.25rem;
  font-weight: bold;
  padding: 0.1rem;
  color: var(--gray-50);
  background-color: var(--gray-400);
}
.key-partner-title {
  width: 100%;
  font-size: 1.25rem;
  font-weight: bold;
  padding: 0.1rem;
  color: var(--gray-50);
  background-color: var(--green-300);
}
.advisors-card{
  display: flex;
  width: 70vw;
  overflow: clip;
}
.advisors .card {
  width: 35%;
  height: 20rem;
  padding: 0;
  overflow: clip;
}
.partners {
  width: 30vw;
  overflow: clip;
}
.partners-logo{
  width: 100%;
  height: 20rem;
  padding: 0;
  overflow: clip;
  background-color: var(--gray-150)
}
</style>