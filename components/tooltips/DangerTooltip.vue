<template>
  <div class="bg-lvv-blue-600 text-white p-2 font-semibold">
    {{ feature.properties.name }}
  </div>
</template>

<script setup lang="ts">
import type { DangerFeature } from '~/types';

const { feature } = defineProps<{
  feature: DangerFeature
}>();

</script>
