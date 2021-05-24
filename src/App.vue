<template>
  <div id="app w-screen">
    <Home msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>


import Home from "@/components/Home";

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;

}
</style>
