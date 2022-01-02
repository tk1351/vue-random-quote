<template>
  <div class="detail">
    <div class="detail__info">
      <QuoteAuthorName />
      <QuoteAuthorGenre />
    </div>
    <div>
      <QuoteArrowIcon />
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteAuthorName from "../atoms/QuoteAuthorName.vue";
import QuoteAuthorGenre from "../atoms/QuoteAuthorGenre.vue";
import QuoteArrowIcon from "../atoms/QuoteArrowIcon.vue";

export default defineComponent({
  components: {
    QuoteArrowIcon,
    QuoteAuthorGenre,
    QuoteAuthorName
  }
})
</script>

<style scoped>
.detail {
  height: 100px;
  margin: 60px 80px 0 80px;
  background-color: darkkhaki;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

.detail__info {
  display: flex;
  flex-direction: column;
}
</style>