<script lang="ts" setup>
import { useAsyncState } from "@vueuse/core";

definePageMeta({
  keepalive: true
});

const route = useRoute();
const id = route.params.id || "undefined";
</script>

<template>
  <div>
    Product {{ id }}
  </div>
</template>

<style lang="less">
</style>