<script lang="ts">
  export default {
    inheritAttrs: false,
  };
</script>

<script setup lang="ts">
  defineProps({ msg: String });
</script>

<template>
  <h1>HelloWorldMultiple {{ msg }}</h1>
</template>

<style scoped></style>
