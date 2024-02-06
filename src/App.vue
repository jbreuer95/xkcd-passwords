<template>
<div class="w-80 p-3">
  <div id="toast-undo" class="flex items-center justify-between px-4 h-12 text-gray-400 bg-gray-800 rounded-lg shadow" role="alert">
      <div class="text-base font-normal bold">
        lorem ipsum dolar sit amit
      </div>
  </div>
  <div class="flex justify-between mt-2">
    <div class="flex flex-col justify-between gap-3 pt-1.5">
      <div class="px-2">
          <input type="checkbox" value="" class="w-4 h-4 text-blue-600 rounded focus:ring-blue-600 ring-offset-gray-800 focus:ring-2 bg-gray-700 border-gray-600">
          <label class="ms-2 text-sm font-medium text-gray-300">
            Symbols
          </label>
      </div>
      <div class="px-2">
          <input type="checkbox" value="" class="w-4 h-4 text-blue-600 rounded focus:ring-blue-600 ring-offset-gray-800 focus:ring-2 bg-gray-700 border-gray-600">
          <label class="ms-2 text-sm font-medium text-gray-300">
            Uppercase
          </label>
      </div>
      <div class="px-2">
          <input type="checkbox" value="" class="w-4 h-4 text-blue-600 rounded focus:ring-blue-600 ring-offset-gray-800 focus:ring-2 bg-gray-700 border-gray-600">
          <label class="ms-2 text-sm font-medium text-gray-300">
            Numbers
          </label>
      </div>
    </div>
    <div class="flex items-start">
      <div class="flex items-center">
          <button type="button" class="text-gray-500 hover:text-white rounded-lg focus:ring-2 focus:ring-gray-300 p-1.5 hover:bg-gray-700 inline-flex items-center justify-center h-8 w-8" data-dismiss-target="#toast-undo" aria-label="Close">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0 3.181 3.183a8.25 8.25 0 0 0 13.803-3.7M4.031 9.865a8.25 8.25 0 0 1 13.803-3.7l3.181 3.182m0-4.991v4.99" />
            </svg>
        </button>
      </div>
      <div class="flex items-center ml-2">
          <button type="button" class="text-gray-500 hover:text-white rounded-lg focus:ring-2 focus:ring-gray-300 p-1.5 hover:bg-gray-700 inline-flex items-center justify-center h-8 w-8" data-dismiss-target="#toast-undo" aria-label="Close">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M15.666 3.888A2.25 2.25 0 0 0 13.5 2.25h-3c-1.03 0-1.9.693-2.166 1.638m7.332 0c.055.194.084.4.084.612v0a.75.75 0 0 1-.75.75H9a.75.75 0 0 1-.75-.75v0c0-.212.03-.418.084-.612m7.332 0c.646.049 1.288.11 1.927.184 1.1.128 1.907 1.077 1.907 2.185V19.5a2.25 2.25 0 0 1-2.25 2.25H6.75A2.25 2.25 0 0 1 4.5 19.5V6.257c0-1.108.806-2.057 1.907-2.185a48.208 48.208 0 0 1 1.927-.184" />
            </svg>
        </button>
      </div>
    </div>
  </div>
  <div class="mx-2 mt-2 relative mb-6">
    <label class="text-sm font-medium text-gray-300 ">Words</label>
    <input type="range" min="3" max="6" value="4" class="w-full h-2 rounded-lg appearance-none cursor-pointer bg-gray-700">
    <span class="text-sm text-gray-400 absolute start-0 -bottom-6">3</span>
    <span class="text-sm text-gray-400 absolute start-1/3 -translate-x-1/2 rtl:translate-x-1/2 -bottom-6">4</span>
    <span class="text-sm text-gray-400 absolute start-2/3 -translate-x-1/2 rtl:translate-x-1/2 -bottom-6">5</span>
    <span class="text-sm text-gray-400 absolute end-0 -bottom-6">6</span>
  </div>
</div>
</template>

<script setup>

</script>
