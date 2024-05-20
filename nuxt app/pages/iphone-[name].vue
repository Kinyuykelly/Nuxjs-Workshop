<script setup>

const route = useRoute();
const name = computed(()=> {
    return route.params.name.replaceAll("-", " ");
})
</script>
<template>
    <div>
        Iphone {{ name }}
    </div>
</template>