<script setup></script>

<template>
  <button class="button">
    <div>
      <slot name="icon" />
    </div>
    <slot />
  </button>
</template>

<style scoped>
.button {
  border: none;
  border-radius: 10px;
  background: var(--gradient);
  padding: 14px;
  font-family: var(--font-montserrat);
  font-size: 20px;
  font-weight: 600;
  color: var(--color-primary);
  cursor: pointer;
}
.button:hover {
  background: var(--gradient-inverted);
}
</style>