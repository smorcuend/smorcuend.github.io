<template>
  <NextTimeline :items="items" />
</template>

<script setup>
import NextTimeline from "./NextTimeline.vue";
const items = [
    {
    title: "2011-13",
    content:
      '<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/Logo_UC3M.svg/2048px-Logo_UC3M.svg.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#6B207B"
  },
  {
    title: "2013-16",
    content:
      '<img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Logo-BQ-CasoDeExito.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#6B207B"
  },
  {
    title: "2016-18",
    content: 'Seedtag <img src="https://startupxplore.com/uploads/ff8080815674a090015674a1ed2700bd-large.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#C18B6E"
  },
  {
    title: "2018",
    content: '<img src="https://tscfo.com/wp-content/uploads/2021/05/graphext.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#2857A7"
  },
  {
    title: "2018-21",
    content: '<img src="https://reclamador-static.s3.amazonaws.com/static/web/images/logo-reclamador.692ed3f5445c.svg" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#399"
  },
    {
    title: "2020",
    content: 'Bloomod<img src="https://assets.website-files.com/5b9b7195899c180185cdf08f/5c190b272b5007440ce69100_AF_WAYRA_LOGO_RGB_POS.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#666"
  },
  {
    title: "2021-",
    content: '<img src="https://www.kairosds.com/assets/images/kw-tab-list/logo-cesefor.png" height="50" width="80" style="margin: 0 auto;"/>',
    color: "#FDBE00"    
  }
];
</script>
