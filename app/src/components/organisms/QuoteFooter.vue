<template>
  <div class="footer">
    <QuoteAppDescription />
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteAppDescription from "../atoms/QuoteAppDescription.vue";

export default defineComponent({
  components: {QuoteAppDescription}
})
</script>

<style scoped>
.footer {
  height: calc(100vh - 95vh);
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: darkgray;
}
</style>