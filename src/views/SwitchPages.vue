<script setup>
import { ref, defineOptions} from "vue";
// import AboutUs from '@/landing_page/components/AboutUs.vue';
import InterfaceFeatures from '@/components/InterfaceFeatures.vue';
import UseCases from '@/components/UseCases.vue';
import TeamOverview from '@/components/TeamOverview.vue';
import ContactUs from '@/components/ContactUs.vue';

defineOptions({
  name: "SwitchPages",
});

const currentModule = ref('InterfaceFeatures')

const components = {
  InterfaceFeatures,
  UseCases,
  TeamOverview,
  ContactUs
}

</script>

<template>
  <div>
  <span class="buttons" :class="{ active: currentModule === 'InterfaceFeatures' }"
        @click="currentModule = 'InterfaceFeatures'">Interface Features</span>
    <span class="buttons" :class="{ active: currentModule === 'UseCases' }"
          @click="currentModule = 'UseCases'">Use Cases</span>
    <span class="buttons" :class="{ active: currentModule === 'TeamOverview' }"
          @click="currentModule = 'TeamOverview'">Team Overview</span>
    <span class="buttons" :class="{ active: currentModule === 'ContactUs' }"
          @click="currentModule = 'ContactUs'">Contact Us</span>
  </div>
  <component :is="components[currentModule]"></component>

</template>

<style scoped>
div {
  display: flex;
  align-items: center;
}

.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 25%;
  height: 4rem;
  padding: 0.5rem 1rem;
  background-color: var(--gray-200);
  border: none;
  color: var(--gray-700);
  font-weight: bold;
  font-size: 1.5rem;
  cursor: pointer;
}

.active {
  color:var(--gray-50);
  background-color: var(--green-200);
}
</style>