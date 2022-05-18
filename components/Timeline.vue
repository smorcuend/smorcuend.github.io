<template>
  <vue-horizontal-timeline :items="items" timeline-background="transparent" />
</template>

<script setup>
import VueHorizontalTimeline from "vue-horizontal-timeline";
const example1 = {
  title: "Title example 1",
  content:
    "Lorem ipsum dolor sit amet, consectetur adipiscin",
  stepCssClass: 'has-step-green',
  boxCssClass: 'has-color-red'
};
const example2 = {
  title: "Title example 2",
  content:
    "Lorem ipsum dolor sit amet."
};
const example3 = {
  title: "Title example 3",
  content:
    "Lorem ipsum dolor sit amet,"
};
const items = [example1, example2, example3];
</script>

<style scoped>
.vue-horizontal-timeline {
  box-shadow: none;
}
</style>
