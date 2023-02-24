<script setup>

</script>

<template>
  <div mx-auto container space-y-20 text="gray-700 dark:gray-200" p="x-4" m="b-4">
    <section grid="~ lg:cols-3" gap="y-1 x-6">
      <h2 text="2xl" tracking-tight>
        <slot name="title" />
      </h2>
      <div grid="lg:col-span-2" prose text-lg max-w-7xl>
        <slot />
      </div>
    </section>
  </div>
</template>
