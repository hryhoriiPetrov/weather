<script setup>
import Stat from './components/Stat.vue';
import Button from './components/Button.vue';
</script>

<template>
  <main class="main">
    <Stat />
    <Button>
      <template #icon>
        +
      </template>
      Сохранить
    </Button>
  </main>
</template>

<style scoped>
.main {
  border-radius: 25px;
  background-color: var(--color-bg-main);
  padding: 60px 50px;
}
</style>
