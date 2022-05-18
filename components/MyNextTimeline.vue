<template>
  <NextTimeline :items="items" />
</template>

<script setup>
import NextTimeline from "./NextTimeline.vue";
const items = [
  {
    title: "2011",
    content:
      '<img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Logo-BQ-CasoDeExito.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#6B207B"
  },
  {
    title: "2012",
    content: "Seedtag",
    color: "#C18B6E"
  },
  {
    title: "2015",
    content: "Graphext",
    color: "#2857A7"
  },
  {
    title: "2018",
    content: "Reclamador S.L",
    color: "#399"
  },
  {
    title: "2021",
    content: "Cesefor",
    color: "#FDBE00"
  }
];
</script>
