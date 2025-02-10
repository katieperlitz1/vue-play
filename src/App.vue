<script setup>
import Section from '@/components/Section.vue';
import { ref } from 'vue';
import draggable from 'vuedraggable';

</script>

<template>
  <div class="main">
  <p class="head">Open Loops</p>
  <Section />
</div>
</template>

<style scoped>
.head {
  font-family: system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 40px;
  font-weight: bold;
  margin:0;
}
.main {
  font-family: system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  padding: 40px;
  align-items: center;
}
</style>
