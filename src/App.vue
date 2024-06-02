<template>
  <NavBar />
  <router-view :key="$router.fullpath"/>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style scoped></style>