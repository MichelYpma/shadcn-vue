<script setup lang="ts">
import { Button } from '@/lib/registry/new-york/ui/button'
import { ReloadIcon } from '@radix-icons/vue'
</script>

<template>
  <Button disabled>
    <ReloadIcon class="w-4 h-4 mr-2 animate-spin" />
    Please wait
  </Button>
</template>
