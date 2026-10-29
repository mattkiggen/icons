<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "hand holding money",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <path
        d="m10.437,12.965l4.817-2.174c.712-.321,1.549-.005,1.871.707h0c.321.712.005,1.549-.707,1.871l-6.791,3.065c-.676.305-1.441.349-2.148.123l-4.478-1.432"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></path>
      <path
        d="m7.245,12.098l1.971.894c.711.323,1.549.008,1.872-.703h0c.323-.711.008-1.549-.703-1.872l-2.777-1.268c-2.296-1.023-4.233.539-4.608,2.352"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></path>
      <path
        d="m.75,9.75h1.25c.552,0,1,.448,1,1v5c0,.552-.448,1-1,1H.75"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></path>
      <path
        d="m10.75,6.5c.966,0,1.75-.784,1.75-1.75s-.784-1.75-1.75-1.75-1.75.784-1.75,1.75.784,1.75,1.75,1.75Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m6.25,1.25c-.5522,0-1,.4478-1,1v1.7498c1.5179,0,2.7499-1.2317,2.75-2.7498h-1.75Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m15.25,1.25c.5522,0,1,.4478,1,1v1.7498c-1.5179,0-2.7499-1.2317-2.75-2.7498h1.75Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m15.25,8.25c.5522,0,1-.4478,1-1v-1.7498c-1.5179,0-2.7499,1.2317-2.75,2.7498h1.75Z"
        fill="#212121"
        stroke-width="0"
      ></path>
      <path
        d="m12.5276,8.25h2.7224c.5523,0,1-.4477,1-1V2.25c0-.5523-.4477-1-1-1H6.25c-.5523,0-1,.4477-1,1v3.595"
        fill="none"
        stroke="#212121"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="1.5"
      ></path>
    </g>
  </svg>
</template>
