<script>
  export default {
    inheritAttrs: false,
  };
</script>

<script setup>
  defineProps({ msg: String });
</script>

<template>
  <h1>HelloWorldMultiple {{ msg }}</h1>
</template>

<style scoped></style>
