<script setup lang="ts">
interface Props {
  title?: string;
}
const props = withDefaults(defineProps<Props>(), {
  title: "file shield",
});
</script>
<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18">
    <title>{{ title }}</title>
    <g fill="#212121">
      <path
        d="M5.75 6.75H7.75"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M5.75 9.75H9.7662"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M15.16 6.25H11.75C11.198 6.25 10.75 5.802 10.75 5.25V1.85201"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M15.25 7.8461V6.664C15.25 6.399 15.145 6.144 14.957 5.957L11.043 2.043C10.855 1.855 10.601 1.75 10.336 1.75H4.75C3.645 1.75 2.75 2.646 2.75 3.75V14.25C2.75 15.354 3.645 16.25 4.75 16.25H8.94901"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
      <path
        d="M14.5 10.75L11.75 12V14.94C11.75 16.48 14.5 17.25 14.5 17.25V10.75Z"
        fill="#212121"
        stroke="none"
      ></path>
      <path
        d="M14.5 10.75L17.25 12V14.94C17.25 16.48 14.5 17.25 14.5 17.25C14.5 17.25 11.75 16.48 11.75 14.94V12L14.5 10.75Z"
        stroke="#212121"
        stroke-width="1.5"
        stroke-linecap="round"
        stroke-linejoin="round"
        fill="none"
      ></path>
    </g>
  </svg>
</template>
