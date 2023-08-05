<script setup lang="ts">
import { computed } from "vue";

// add prop text
const props = defineProps(["pageId"]);
// computed
const pageLink = computed(() => {
  return "#" + props.pageId;
});
</script>
<template>
  <div>
    <div class="title">{{ props.pageId }}</div>
    <a :href="pageLink">
      <img class="down" src="../assets/down.png" />
    </a>
  </div>
</template>

<style scoped>
.title {
  font-size: 1.8em;
}
div {
  margin: 10px;
}
</style>
