<script setup>
const count = ref(0);

function add(){
  count.value++;
}
function subtract(){
  count.value--;
}
</script>

<template>
    <div>
    <button @click="add">Increment</button>
    <p>{{ count }}</p>
    <button @click="subtract">Decrement</button>
    </div>
</template>