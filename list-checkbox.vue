<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "list checkbox 2",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 12 12">
    <title>{{ title }}</title>
    <g fill="#212121">
      <path
        d="M6.75 3.25H11.25"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M6.75 8.75H11.25"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M4.1295 1.375L1.87725 4.375L0.75 3.25"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M4.1295 7.375L1.87725 10.375L0.75 9.25"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
    </g>
  </svg>
</template>
