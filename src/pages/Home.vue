<script setup lang="ts">
import useTestStore from '../store/test'
const testStore = useTestStore()
</script>

<template>
  <h2>{{testStore.data}} Home Page!!!</h2>
</template>

