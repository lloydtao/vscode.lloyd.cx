<template>
  <div id="terminal-cli" class="flex py-1 px-4">
    <ul class="flex-col w-full text-gray-100 text-sm font-mono overflow-hidden">
      <ul class="flex justify-start space-x-1">
        <li class="text-green-500">LloydTao@DESKTOP</li>
        <li class="text-purple-500">MINGW64</li>
        <li class="text-yellow-300">~/GitHub/vscode.lloyd.cx</li>
        <li class="text-cyan-500">(main)</li>
      </ul>
      <ul class="flex w-full justify-self-star">
        <li class="pr-2">&#36;</li>
        <ul class="flex h-32 w-full">
          <span
            class="input w-full outline-none"
            role="textbox"
            contenteditable
          />
        </ul>
      </ul>
    </ul>
  </div>
</template>
