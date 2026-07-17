<template>
    <nav class="bg-gray-800 text-white px-6 py-4 flex items-center justify-between">
        <div class="font-bold text-xl">MyLMS</div>

        <ul class="flex gap-6">
            <li v-for="link in navLinks" :key="link.id">
                <a :href="link.url" class="hover:text-blue-400">
                    {{ link.label }}
                </a>
            </li>
        </ul>
    </nav>
</template>

<script setup>
import { ref } from 'vue'

const navLinks = ref([
    { id: 1, label: 'Home', url: '/' },
    { id: 2, label: 'Courses', url: '/courses' },
    { id: 3, label: 'About', url: '/about' },
])
</script>