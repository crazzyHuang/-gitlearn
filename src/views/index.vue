<template>
  <div>
    <!-- -->
    <div>my new vue file</div>
    <div>hello world</div>
  </div>
</template>

<script setup>
import { ref, computed } from 'vue'
import { useStore } from 'pinia'
const store = useStore()
const count = computed(() => store.count)
</script>
