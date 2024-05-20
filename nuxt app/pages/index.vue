<script setup lang="ts">
function moveToAbout(){
    navigateTo('about')
}
</script>

<template>
   <div>
   
   hello index
   <button @click="moveToAbout">Take me to About page</button>
   </div>
</template>