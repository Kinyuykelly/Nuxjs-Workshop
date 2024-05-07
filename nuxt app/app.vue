<script setup>
const page  = ref("home");
function view(name){
  page.value = name;
}

</script>
<template>
  <a href="#" @click="view('home')">Home</a>
  <a href="#"  @click="view('counter')">Counter</a>
  <LazyHomeWelcome  v-if="page === 'home'" />
  <LazyCounter  v-if="page === 'counter'" /> 
</template>
