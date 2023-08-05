<script setup lang="ts">
import DownArrow from "../components/DownArrow.vue";
const props = defineProps({
  nextpage: {
    type: String,
    required: false,
  },
  page: {
    type: String,
    required: false,
  },
});
</script>
<template>
  <div class="page" :id="props.page">
    <div>
      <slot></slot>
    </div>
    <DownArrow v-if="props.nextpage" :pageId="props.nextpage" />
  </div>
</template>

<style>
.page {
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  max-width: 80%;
  scroll-snap-align: start;
}
</style>
