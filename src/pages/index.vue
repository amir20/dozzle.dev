<script setup lang="ts">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <main>
    <hero />
    <features />
    <installation />
  </main>

  <router-link to="/guide/what-is-dozzle">
    What is Dozzle?
  </router-link>

  <router-link to="/guide/getting-started">
    Getting Started
  </router-link>

  <router-link to="/test">
    test
  </router-link>
</template>
