<script setup lang="ts">
</script>
<template>
  <div class="navbar">
    <h1 class="poppins-brand middle">avnce</h1>
    <div class="end">
      <router-link to="/about" class="e1">About</router-link>
      <router-link to="/contact" class="e2">Contact</router-link>
    </div>
  </div>
</template>
<style scoped>
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 75px;
  background: #353535;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  z-index: 1;
  color: white;
}
.end {
  position: absolute;
  top: 50%;
  right: -10px;
  transform: translate(-50%, -50%);
}
.e1 {
  margin-right: 10px;
}
.e2 {
  margin-left: 15px;
}
.middle {
  position: absolute;
  top: 50%;
  transform: translate(50%, -50%);
}
.poppins-brand {
  font-family:'Poppins', sans-serif;
  src: url('/poppins/Poppins-Bold.ttf');
}
</style>