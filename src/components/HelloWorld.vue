<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>
  <h2>This project is all about learning!</h2>
</template>

<style scoped>
a {
  color: #42b983;
}
h2 {
  background-color: yellow;
}
</style>
