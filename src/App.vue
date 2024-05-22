<template>
  <div id="app">

    <ConTrau mota="Mô tả con trâu"/>

  </div>
</template>

<script>


import ConTrau from "@/components/Trau.vue";

export default {
  name: 'App',
  components: {
    ConTrau
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
