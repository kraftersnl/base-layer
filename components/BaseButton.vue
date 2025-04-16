<script setup lang="ts">
defineProps<{ label: string }>();

const buttonRef = useTemplateRef('btn');
</script>

<template>
  <button ref="btn">{{ label }}</button>
</template>
