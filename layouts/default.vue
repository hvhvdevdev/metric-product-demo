<script setup>
useHead({
  bodyAttrs: {
    class: "body",
  },
});
</script>

<template>
  <StatusBar></StatusBar>
  <AppHeader></AppHeader>
  <main>
    <Breadcrumb></Breadcrumb>
  </main>
  <NuxtPage> </NuxtPage>
  <AppFooter></AppFooter>
</template>

<style>
.body {
  margin: 0;
  width: 100%;
  height: 100%;
  font-family:
    ui-sans-serif,
    system-ui,
    -apple-system,
    "Segoe UI",
    Roboto,
    Ubuntu,
    Cantarell,
    "Noto Sans",
    sans-serif,
    BlinkMacSystemFont,
    "Helvetica Neue",
    Arial,
    "Apple Color Emoji",
    "Segoe UI Emoji",
    "Segoe UI Symbol",
    "Noto Color Emoji";
}

main {
  width: 840px;
  margin: auto;
}
</style>
