<template>
  <div class="relative flex-none px-5 mt-0 w-full max-w-full text-center md:w-1/2 md:flex-none lg:w-1/3 lg:flex-none">
    <div class="mb-4">
      <slot></slot>
    </div>
    <h3 class="mt-0 mb-2 text-xl font-semibold tracking-normal text-white">{{ label }}</h3>
    <p class="mt-0 mb-12 md:mb-0 text-gray-400">
      {{ description }}
    </p>
  </div>
</template>

<script setup>
const props = defineProps({
  label: {
    required: true,
    type: String
  },
  description: {
    required: true,
    type: String
  },
})
</script>
