<template>
  <div class="grid">
    <div v-for="n in 5" class="rows">
      <Cell v-for="m in 5">({{ m }}, {{ n }})</Cell>
    </div>
  </div>

</template>

<script setup lang="ts">
import Cell from "./Cell.vue"
</script>

<style scoped lang="scss">
.grid {
  display: flex;
  flex-direction: column;
}
.rows {
  display: flex;
  flex-direction: row;
}
</style>