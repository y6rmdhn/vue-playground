<script setup>
import CompositionComponent from './components/CompositionComponent.vue'
import MainButton from './components/MainButton.vue'
import OptionsComponent from './components/OptionsComponent.vue'

const name = 'fira'
</script>

<template>
  <main>
    <h1>Hello World!</h1>
    <p>{{ name }}</p>
    <MainButton />
    <OptionsComponent />
    <CompositionComponent />
  </main>
</template>

<style scoped></style>
