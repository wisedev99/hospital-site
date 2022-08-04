<template>
  <div class="flex-grow w-full h-full overflow-hidden  p-4 mx-auto max-w-7xl">
    <header class="w-full">
          <slot name="header" v-if="header" />
          <span v-else>Nuxt 3</span>
    </header>
    <main class="flex-grow w-full h-full p-4 mx-auto max-w-7xl">
      <slot />
    </main>
    <footer class="flex items-center justify-center w-full h-16 text-black">
        <p class="text-gray-700">
          My Nuxt App &copy; {{ new Date().getFullYear() }}
        </p>
    </footer>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  computed: {
    header() {
      return this.$slots.header
    }
  }
})
</script>
