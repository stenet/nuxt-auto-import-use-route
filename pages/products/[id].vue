<script lang="ts" setup>
//import { useRoute } from "vue-router";

const route = useRoute();
const path = route.path;
const id = route.params.id || "undefined";
</script>

<template>
  <div>
    <div>
      Product {{ id }}
    </div>
    <div>
      Current route <b>{{ path }}</b> - should be <b>/product/123</b>
    </div>
  </div>
</template>

<style lang="less">
</style>