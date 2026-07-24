<script setup lang="ts">
import { Head } from '@inertiajs/vue3';
import { main } from '@/routes';

defineOptions({
  layout: {
    breadcrumbs: [
      {
        title: 'main',
        href: main(),
      },
    ],
  },
});
</script>

<template>
  <Head title="Древо жизни" />

</template>