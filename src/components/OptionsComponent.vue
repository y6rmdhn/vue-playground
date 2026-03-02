<script>
export default {
  data() {
    return {
      name: 'firaaaaaaa',
    }
  },
  methods: {
    showName() {
      console.log(this.name)
    },
  },
}
</script>

<template>
  <h1>
    {{ name }}
  </h1>
  <button @click="showName">show name in console</button>
</template>
