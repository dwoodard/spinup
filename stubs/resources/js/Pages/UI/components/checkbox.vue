<script setup lang="ts">
import { Checkbox } from '@/Components/ui/checkbox'
import Layout from '@/Layouts/UI/Components.vue'
</script>

<template>
  <Layout>
    <div class="flex items-center space-x-2">
      <Checkbox id="terms" />
      <label
        for="terms"
        class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
      >
        Accept terms and conditions
      </label>
    </div>
  </Layout>
</template>
