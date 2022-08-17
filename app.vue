<template>
  <div>
    <!--<NuxtPage />-->
    
    <RouterView v-slot="{ Component, route }">
      <KeepAlive :max="2">
        <Component :is="Component" :key="route.path"/>
      </KeepAlive>
    </RouterView>
  </div>
</template>
