<script setup></script>

<template>
  <div class="stat">
    <span class="stat-name">влажность</span>
    <span class="stat-value">90%</span>
  </div>
</template>

<style scoped>
.stat {
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-size: 28px;
  line-height: 1;
  gap: 16px;
}
.stat-name {
  font-weight: 700;
  text-transform: uppercase;
}
.stat-value {
  font-weight: 500;
}
</style>