<template>
  <Button type="primary" @click="active = !active">
    打开
  </Button>
  <Modal
    v-model:active="active"
    transfer
    title="标题"
    :width="500"
  >
    <p>一些内容</p>
    <p>一些内容</p>
    <p>一些内容</p>
  </Modal>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const active = ref(false)
</script>
