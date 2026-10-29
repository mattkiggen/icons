<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "xmark",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <line
        x1="14"
        y1="4"
        x2="4"
        y2="14"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
      <line
        x1="4"
        y1="4"
        x2="14"
        y2="14"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
    </g>
  </svg>
</template>
