<template>
  <div id="app">
    <!-- <span class="icon-back"></span>
    <img src="./assets/logo.png"> -->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "App"
};
document.addEventListener("DOMContentLoaded", () => {
  const html = document.querySelector('html')
  let fontSize = window.innerWidth / 10
  fontSize = fontSize > 50 ? 50 : fontSize
  // html.style.fontSize = window.innerWidth / 10 + 'px'
  html.style.fontSize = fontSize  + 'px'
});
</script>

<style>

</style>
