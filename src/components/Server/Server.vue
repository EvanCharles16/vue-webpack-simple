<template>
  <li
    class="list-group-item"
    style="cursor : pointer"
    @click="serverSelected"
  >Server #{{ serverProps.id }}</li>
</template>

<script>
import { serverBus } from "./../../main";
export default {
  // Passing props from Servers.vue
  props: ["serverProps"],
  methods: {
    serverSelected() {
      serverBus.$emit("serverSelected", this.serverProps);
    },
  },
};
</script>

<style scoped>
</style>