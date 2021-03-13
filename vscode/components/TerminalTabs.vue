<template>
  <div class="flex items-center justify-between">
    <ul
      class="flex items-center space-x-4 text-gray-400 text-xs uppercase px-4 py-2"
    >
      <li class="p-1">Problems</li>
      <li class="p-1">Output</li>
      <li class="p-1">Debug Console</li>
      <li class="text-gray-100 border-b p-1">Terminal</li>
    </ul>
    <ul
      class="flex justify-end items-center space-x-4 text-gray-100 text-sm px-4 py-2"
    >
      <li class="flex w-48 justify-between items-center bg-gray-800 px-1 py-1">
        <div class="px-2">1: bash</div>
        <div class="w-4 mr-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-chevron-down"
          >
            <polyline points="6 9 12 15 18 9"></polyline>
          </svg>
        </div>
      </li>
      <li class="flex items-center w-4 text-gray-200">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="2 2 22 22"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M12 6v6m0 0v6m0-6h6m-6 0H6"
          />
        </svg>
      </li>
      <li class="flex items-center w-4 text-gray-200">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"
          />
        </svg>
      </li>
      <li class="flex items-center w-4 text-gray-200">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M5 15l7-7 7 7"
          />
        </svg>
      </li>
      <li class="flex items-center w-4 text-gray-200">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="feather feather-x"
        >
          <line x1="18" y1="6" x2="6" y2="18"></line>
          <line x1="6" y1="6" x2="18" y2="18"></line>
        </svg>
      </li>
    </ul>
  </div>
</template>
