<script setup lang="ts">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div grid="~ lg:cols-3 lg:gap-8" h-full mx-auto>
    <div flex="~ col" text="center" p="x-4">
      <h1 text-4xl my-auto font-extralight>
        <span font-playfair>Dozzle</span> is a modern log viewer
        for Docker providing efficient and intuitive ways to
        view and search logs from containers
      </h1>
    </div>
    <div grid="lg:col-span-2" flex>
      <div my-auto>
        <browser-window>
          <video muted loop autoplay playsinline>
            <source src="../media/dozzle.webm" type="video/webm">
            <source src="../media/dozzle.mp4" type="video/mp4">
          </video>
        </browser-window>
      </div>
    </div>
  </div>
</template>
