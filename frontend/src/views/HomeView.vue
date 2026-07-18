<script setup>
import Card from '../components/Card.vue'
</script>

<template>
  <section
    class="bg-[url('../images/hero.jpg')] bg-cover bg-center min-h-[500px] flex items-center justify-center py-20 px-6">
    <h1 class="font-bold mb-4 text-4xl text-white drop-shadow-black drop-shadow-lg">This is a hero section</h1>
  </section>

  <section class="bg-gray-700 min-h-200 px-6 py-8">
    <Card icon="" title="Course 1" description="course 1 description" />

  </section>

</template>