<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "calendar days",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <line
        x1="5.75"
        y1="3.25"
        x2="5.75"
        y2="1.25"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
      <line
        x1="12.25"
        y1="3.25"
        x2="12.25"
        y2="1.25"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
      <rect
        x="2.25"
        y="3.25"
        width="13.5"
        height="12.5"
        rx="2"
        ry="2"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></rect>
      <line
        x1="2.25"
        y1="6.75"
        x2="15.75"
        y2="6.75"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></line>
      <path
        d="m9,8.75c-.551,0-1,.449-1,1s.449,1,1,1,1-.449,1-1-.449-1-1-1Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m12.5,10.75c.551,0,1-.449,1-1s-.449-1-1-1-1,.449-1,1,.449,1,1,1Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m9,11.75c-.551,0-1,.449-1,1s.449,1,1,1,1-.449,1-1-.449-1-1-1Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m5.5,11.75c-.551,0-1,.449-1,1s.449,1,1,1,1-.449,1-1-.449-1-1-1Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m12.5,11.75c-.551,0-1,.449-1,1s.449,1,1,1,1-.449,1-1-.449-1-1-1Z"
        fill="#212121"
        stroke-width="0"
      ></path>
    </g>
  </svg>
</template>
