<template>
  <Header />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
  <Footer />
</template>

<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.1s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(0.25rem);
}
</style>
