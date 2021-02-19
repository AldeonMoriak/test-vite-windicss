<template>
  <div class="border-t-4 border-purple-500 bg-gray-200" dir="rtl">
    <main class="max-w-2xl lg:max-w-6xl mx-auto px-6">
      <article class="border-t-2 border-gray-100 grid lg:grid-cols-3 lg:gap-16">
        <Filters />
        <Test class="py-12" />
      </article>
    </main>
  </div>
</template>

<script setup>
import Filters from "./components/Filters.vue";
import Test from "./components/Test.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>