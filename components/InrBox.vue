<script setup lang="ts">
// Encart « Fil INR » présent dans chaque séquence
const props = defineProps<{
  title?: string
}>()
</script>

<template>
  <div class="nb-inr nb-fill-lime">
    <div class="nb-inr-label nb-fill-navy">🌱 Fil INR<span v-if="props.title"> · {{ props.title }}</span></div>
    <slot />
  </div>
</template>

<style scoped>
.nb-inr {
  position: relative;
  border: var(--nb-border);
  box-shadow: var(--nb-shadow);
  padding: 1.6rem 1.2rem 1rem;
  margin-top: 1.4rem;
}

.nb-inr-label {
  position: absolute;
  top: -1rem;
  left: 1rem;
  font-family: 'Archivo Black', sans-serif;
  font-size: 0.9rem;
  padding: 0.2rem 0.7rem;
  transform: rotate(-2deg);
}
</style>
