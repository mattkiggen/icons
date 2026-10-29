<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "arrows opposite direction x",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <polyline
        points="5.5 9.5 2.25 6.25 5.5 3"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></polyline>
      <line
        x1="2.25"
        y1="6.25"
        x2="10.25"
        y2="6.25"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
      <polyline
        points="12.5 15 15.75 11.75 12.5 8.5"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></polyline>
      <line
        x1="15.75"
        y1="11.75"
        x2="7.75"
        y2="11.75"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
    </g>
  </svg>
</template>
