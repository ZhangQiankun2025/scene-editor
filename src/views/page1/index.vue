<template>
  <div />
</template>

<script setup lang="ts">
import { useRouter } from 'vue-router'
const router = useRouter()
// Redirect legacy /page1 to new /model-editor route
router.replace('/model-editor')
</script>

