<template>
  <div class="header">
    <QuoteRefreshButton />
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteRefreshButton from "../molecules/QuoteRefreshButton.vue";

export default defineComponent({
  components: {
    QuoteRefreshButton
  }
})
</script>

<style scoped>
.header {
  height: calc(100vh - 95vh);
  display: flex;
  justify-content: flex-end;
  align-items: center;
  background-color: darkgray;
}
</style>
