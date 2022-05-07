<template>
  <div class="rounded-lg py-7 flex flex-col items-center shadow-lg border border-gray-100">
    <slot></slot>
    <p class="font-bold mt-2" v-text="label"></p>
    <p class="mt-2 text-sm text-gray-500" v-text="description"></p>
    <span class="mt-2 bg-gray-100 text-gray-500 text-sm font-semibold mr-2 px-5 py-1.5 rounded dark:bg-blue-200 dark:text-blue-800"
          v-if="soon">Soon</span>
    <template v-if="!soon">
      <span class="mt-2 bg-green-100 text-green-500 text-sm font-semibold mr-2 px-5 py-1.5 rounded dark:bg-blue-200 dark:text-blue-800"
            v-if="free">Free Plan</span>
      <span class="mt-2 bg-blue-100 text-blue-500 text-sm font-semibold mr-2 px-5 py-1.5 rounded dark:bg-blue-200 dark:text-blue-800"
            v-else>Pro Plan</span>
    </template>
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

  soon: {
    required: false,
    default: false,
    type: Boolean
  },

  free: {
    required: false,
    default: false,
    type: Boolean
  },
})
</script>
