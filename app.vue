<template>
  <NuxtLayout :name="$route.path === '/about' ? 'exceptional' : 'common'">
    <NuxtPage />
  </NuxtLayout>
</template>
