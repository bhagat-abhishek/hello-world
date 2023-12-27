<template>
  <div>{{ greeting }} {{ name }}</div>
  <div v-text="channel"></div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      greeting: "Hello",
      name: "Abby",
      channel: "Abbyx"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
