<script setup lang="ts">
const source = ref('')
const body = $ref<HTMLElement>()
onMounted(() => {
  source.value = body?.textContent?.trim() || ''
})

const { text, copy, copied, isSupported } = useClipboard({ source })
</script>

<template>
  <div flex>
    <code ref="body" class="not-prose" @click="copy()">
      <slot />
    </code>
    <a v-if="isSupported" icon-btn :class="copied ? 'i-carbon-checkmark' : 'i-carbon-copy'" text-2xl @click="copy()" />
  </div>
</template>
