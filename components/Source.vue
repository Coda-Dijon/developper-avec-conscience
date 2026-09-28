<script setup lang="ts">
// Crédit de source en bas de slide.
// <Source inr />  → contenu repris de l'Académie NR (CC BY-NC-ND 4.0)
// <Source href="https://..." >Texte</Source>
const props = defineProps<{
  href?: string
  inr?: boolean
}>()
</script>

<template>
  <div class="nb-source">
    <template v-if="props.inr">
      Source :
      <a href="https://academie-nr.org/" target="_blank">Académie NR · Institut du Numérique Responsable</a>
      ·
      <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/deed.fr" target="_blank">CC BY-NC-ND 4.0</a>
    </template>
    <template v-else>
      Source :
      <a v-if="props.href" :href="props.href" target="_blank"><slot /></a>
      <slot v-else />
    </template>
  </div>
</template>

<style scoped>
.nb-source {
  position: absolute;
  left: 3.5rem;
  bottom: 0.9rem;
  font-size: 0.72rem;
  font-weight: 600;
  background: var(--nb-white);
  color: var(--nb-navy);
  border: 2px solid var(--nb-ink);
  padding: 0.1rem 0.5rem;
}

.nb-source a {
  color: inherit;
  text-decoration-thickness: 2px;
}
</style>
