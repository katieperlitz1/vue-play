<script setup>
import { ref } from 'vue';
import draggable from 'vuedraggable';
const homework = ref([
  'Hamburger',
  'Pizza',
  'Spaghetti',
  'Tacos',
  'Teriyaki Chicken',
]);
</script>

<template>
  <p class="title">Class</p>
  <draggable v-model="homework" tag="ul" :animation="600" group="tasks">
    <template #item="{ element: meal }">
      <li>{{ meal }}</li>
    </template>
  </draggable>
</template>

<style scoped>
.title {
    font-size: 25px;
    font-weight: bold;
}
</style>
