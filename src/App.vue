<script setup>
import Stat from "./components/Stat.vue";
import Button from "./components/Button.vue";
import IconLocation from "./icons/IconLocation.vue";

const data = {
  label: "Влажность",
  stat: '90%',
};
</script>

<template>
  <main class="main">
    <Stat v-bind="data" />
    <Stat label="осадки" stat="0%" />
    <Button>
      <IconLocation />
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
