<template>
  <div id="code" class="flex w-full py-1 pl-4">
    <textarea
      v-model="message"
      class="flex-col w-full text-gray-100 text-sm bg-gray-900 outline-none resize-none"
    ></textarea>
  </div>
</template>

<script>
export default {
  data() {
    return { message: 'hello world' }
  },
}
</script>

<style></style>
