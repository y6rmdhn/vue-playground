<script setup>
const name = 'firaaaaaaa2'

const showName = () => {
  console.log(name)
}
</script>

<template>
  <h1>
    {{ name }}
  </h1>

  <button @click="showName">show name in console</button>
</template>
