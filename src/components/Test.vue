<template>
  <div class="col-span-2 space-y-12 bg-white shadow-md my-12">
    <div class="grid grid-cols-3">
      <card v-for="i in [1, 2, 3, 4, 5, 6, 7, 8]" class="mb-14" />
    </div>
  </div>
</template>

<script setup>
import Card from "../components/Card.vue";
</script>