<script lang="ts" setup>
//import { useRoute } from "vue-router";

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