<script setup>
import Button from './components/Button.vue';
const id = 'blue';
</script>

<template>
  <header class="button">лого</header>
  <Button>
    <template #icon>
      +
    </template>
    Сохранить
  </Button>
  <main :id>контент</main>
</template>

<style scoped></style>
