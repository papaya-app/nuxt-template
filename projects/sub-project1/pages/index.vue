<template>
  <nt-button />
  <div>{{ hello() }}</div>
</template>

<script setup lang="ts">
import { NtButton } from '@nuxt-template/components'
import { hello } from '@nuxt-template/utils'
</script>

<style scoped></style>
