<template>
  <div id="app">
    <NavigationBar />
    <div class="wrapper">
      <!-- <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </nav> -->
    </div>

    <!-- <router-view /> -->
  </div>
</template>

<script setup>
import NavigationBar from "./components/NavigationBar.vue";
</script>

<style scoped>
#app {
  width: 100%;
  height: 100vh;
}
</style>
