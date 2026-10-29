<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "view all",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <rect
        x="1.75"
        y="2.75"
        width="7"
        height="5.5"
        rx="1"
        ry="1"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></rect>
      <rect
        x="12.25"
        y="4.75"
        width="4"
        height="8.5"
        rx="1"
        ry="1"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></rect>
      <rect
        x="3.75"
        y="11.25"
        width="5.5"
        height="4"
        rx="1"
        ry="1"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></rect>
    </g>
  </svg>
</template>
