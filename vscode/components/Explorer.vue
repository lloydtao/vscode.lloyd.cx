<template>
  <div class="w-64 bg-gray-800">
    <div>
      <ExplorerTitle />
      <ul class="flex-col text-sm text-gray-100">
        <li
          class="text-xs uppercase font-semibold tracking-wide border-b border-gray-500 px-3 my-1"
        >
          Open Editors
        </li>
        <li
          class="text-xs uppercase font-semibold tracking-wide border-b border-gray-500 px-3 my-1"
        >
          vscode.lloyd.cx
        </li>
        <ExplorerFiles />
        <li
          class="text-xs uppercase font-semibold tracking-wide border-b border-gray-500 px-3 my-1"
        >
          Outline
        </li>
        <li
          class="text-xs uppercase font-semibold tracking-wide border-b border-gray-500 px-3 my-1"
        >
          Timing
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
