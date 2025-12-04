<template>
  <el-rate v-model="form.evaluationStars" disabled show-score />
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const value = ref(3.7)
</script>
