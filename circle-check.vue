<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "circle check",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <circle
        cx="9"
        cy="9"
        r="7.25"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></circle>
      <polyline
        points="5.75 9.25 8 11.75 12.25 6.25"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></polyline>
    </g>
  </svg>
</template>
