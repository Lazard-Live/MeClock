<script setup>
window.onload = function(){
  window.setInterval(function(){
    let now = new Date();
    let clock = document.getElementById("clock");
    clock.innerHTML = now.toLocaleTimeString();
  }, 1000);
};
</script>

<template>
<div id="clock"></div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
