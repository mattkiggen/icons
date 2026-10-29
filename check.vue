<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "check",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <polyline
        points="2.75 9.25 6.75 14.25 15.25 3.75"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></polyline>
    </g>
  </svg>
</template>
