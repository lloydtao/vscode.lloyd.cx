<template>
  <div class="min-w-full bg-gray-500 mx-auto">
    <div class="w-full bg-gray-600">
      <TitleBar />
      <div class="flex flex-1 w-full bg-gray-700">
        <Sidebar />
        <Explorer />
        <div id="main" class="flex-col w-full bg-gray-900">
          <Tabs />
          <Nuxt />
          <Terminal />
        </div>
      </div>
      <FooterBar />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
