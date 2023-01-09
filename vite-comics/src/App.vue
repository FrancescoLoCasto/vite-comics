<script setup>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
</script>

<template>

  <section>
    <!-- Header section  -->
    <AppHeader />
  </section>

  <section>
    <!-- Main Section -->
    <AppMain />
  </section>

</template>


<style lang="scss">
@use './styles/general.scss' as *;
</style>
