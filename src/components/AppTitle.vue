<script setup>
defineProps({
  msg: String,
})

</script>

<template>
  <h1>{{ msg }}</h1>
</template>

<style scoped>
h1 {
  color: red;
  text-align: center;
  margin-top: 60px;
}
</style>
