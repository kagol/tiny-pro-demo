<script setup lang="ts">
import { TinyButton } from '@opentiny/vue'
</script>

<template>
  <div style="margin: 20px;">
    这是一个一级菜单
    <tiny-button v-permission="'test::confirm'" type="primary">确定</tiny-button>
  </div>
</template>