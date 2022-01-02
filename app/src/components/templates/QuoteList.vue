<template>
  <div class="quote-list">
    <QuoteAuthorName :listComponent="true" />
    <ul>
      <li>
        <QuoteItem />
      </li>
      <li>
        <QuoteItem />
      </li>
      <li>
        <QuoteItem />
      </li>
      <li>
        <QuoteItem />
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteAuthorName from "../atoms/QuoteAuthorName.vue";
import QuoteItem from "../atoms/QuoteItem.vue";

export default defineComponent({
  components: {
    QuoteItem,
    QuoteAuthorName
  }
})
</script>

<style scoped>
.quote-list {
  min-height: calc(100vh - 10vh);
  margin: 0 20%;
  background-color: cadetblue;
}

ul {
  margin: 0;
  padding: 0;
}

li {
  list-style: none;
  /*margin: 20px 0;*/
  padding: 40px 0;
}
</style>