<template>
    <canvas class="cell" ref="cell" :width="5" :height="5"></canvas>
  </template>
  <script setup lang="ts"></script>
  <style scoped lang="scss">
  .cell {
    border: 1px solid gray;
    margin-left: -1px;
    margin-bottom: -1px;
  }
  </style>