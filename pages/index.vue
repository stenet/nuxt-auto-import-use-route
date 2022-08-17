<script lang="ts" setup>
const router = useRouter();

function goToProduct(id: number) {
  router.push({
    path: `/products/${id}`
  });
}
</script>

<template>
  <div>
    <div>
      Index
    </div>
    <div>
      <button @click="goToProduct(123)">Go to product 123</button>
    </div>
  </div>
</template>

<style lang="less">
</style>