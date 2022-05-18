<template>
  <div>
    <VueWriter :array="arr" :typeSpeed="100" :eraseSpeed="50" />
  </div>
</template>

<script setup>
import VueWriter from "vue-writer";
const arr = ["Software Development", "IoT - Electronic - Hardware - Maker", "Computer Vision - Artificial Intelligence", "Network Systems - DevOps", "Design & Product Development"]
</script>

<style scoped>

</style>