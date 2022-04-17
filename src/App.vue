<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: ' Website - Wiidede',
  meta: [
    { name: 'description', content: 'Wiidede\'s small website with vitesse template' },
  ],
})
</script>

<template>
  <RouterView />
</template>
