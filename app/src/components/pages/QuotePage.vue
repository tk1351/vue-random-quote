<template>
  <QuoteHeader />
<!--  単一表示-->
  <QuoteMain />

<!--  複数表示-->
<!--  <QuoteList />-->
  <QuoteFooter />
</template>

<script lang="ts">
import {defineComponent} from "vue";
import QuoteHeader from "../organisms/QuoteHeader.vue";
import QuoteFooter from "../organisms/QuoteFooter.vue";
import QuoteMain from "../templates/QuoteMain.vue";
import QuoteList from "../templates/QuoteList.vue";

export default defineComponent({
  components: {
    QuoteList,
    QuoteFooter,
    QuoteHeader,
    QuoteMain
  }
})
</script>