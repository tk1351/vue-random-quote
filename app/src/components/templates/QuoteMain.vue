<template>
  <div class="main">
    <QuoteItem />
    <QuoteAuthorDetail />
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteItem from "../atoms/QuoteItem.vue";
import QuoteAuthorDetail from "../molecules/QuoteAuthorDetail.vue";

export default defineComponent({
  components: {
    QuoteAuthorDetail,
    QuoteItem
  }
})
</script>

<style scoped>
.main {
  min-height: calc(100vh - 10vh);
  margin: 0 20%;
  background-color: cadetblue;
  padding: 100px 0 50px 0;
}
</style>