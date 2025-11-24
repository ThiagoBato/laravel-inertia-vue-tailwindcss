<script setup>
defineProps({
    user: {
        type: String,
        default: "Josh",
    },
});
</script>

<template>
    <h1>About</h1>
    <p>{{ user }}</p>
</template>

<style scoped></style>
