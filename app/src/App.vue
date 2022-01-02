<script lang="ts">
import {defineComponent} from "vue";
import QuotePage from "./components/pages/QuotePage.vue";

export default defineComponent({
  components: {
    QuotePage
  }
})
</script>

<template>
  <QuotePage />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
