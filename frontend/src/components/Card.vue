<template>
    <div class="bg-gray-800 px-8 py-8 max-w-[200px]">
        <img :src="icon" :alt="title" class="w-12 h-12">
        <div class="text-bold text-white">{{ title }}</div>
        <p class="text-gray-400">{{ description }}</p>
    </div>
</template>

<script setup>
defineProps(['title', 'description', 'icon']);
</script>