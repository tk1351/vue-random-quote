<template>
  <button type="button" class="button--refresh">
    <QuoteRandomSpan />
    <QuoteRefreshIcon />
  </button>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteRandomSpan from "../atoms/QuoteRandomSpan.vue"
import QuoteRefreshIcon from "../atoms/QuoteRefreshIcon.vue"

export default defineComponent({
  components: {
    QuoteRandomSpan,
    QuoteRefreshIcon
  }
})
</script>

<style scoped>
.button--refresh {
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100px;
}
</style>