<script lang="ts" setup>
import { ref } from 'vue'
const input = ref('')


</script>

<template>
  <main>
    <form autocomplete="off">
      <el-input v-model="input" style="width: 240px" placeholder="Please input" />
    </form>
    <el-button type="primary">cherry pick</el-button>
  </main>
</template>