<template>
  <div class="columns is-multiline is-vcentered">
    <div
      class="column is-4-desktop is-4-tablet"
      v-for="(personaje, index) of personajes"
      :key="index"
    >
      <div>{{ personaje.id }} {{ personaje.nombre }}</div>
      <img :src="personaje.imagen" />
    </div>
  </div>
</template>

<script>
export default {
  name: "mainsection",
  props: {
    personajes: { type: Array, require: true },
  },
};
</script>

<style>
</style>