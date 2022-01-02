<template>
  <p
      class="name"
      :class="{ 'name--list-component': listComponent }"
  >
    Bill Gates
  </p>
</template>

<script lang="ts">
import {defineComponent} from "vue";

export default defineComponent({
  props: {
    listComponent: {
      type: Boolean
    }
  }
})
</script>

<style scoped>
.name {
  font-size: 19px;
}

.name--list-component {
  font-size: 22px;
  font-weight: bold;
  padding: 20px 80px;
}
</style>