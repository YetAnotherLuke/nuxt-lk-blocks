<template>
  <nav class="flex items-center justify-between flex-wrap bg-gray-100 p-6">
    <div class="flex items-center flex-shrink-0 text-white mr-6">
      <div>
        <fa :icon="{prefix: 'fas', iconName: 'stream'}" class="text-red-600 text-3xl" />
      </div>
      <span class="ml-3 font-semibold text-2xl tracking-tight text-black">Luke Blocks</span>
    </div>
    <div>
      <a href="#" class="inline-block float-right text-sm px-4 py-2 leading-none border rounded text-red-400 border-red-400 hover:border-red-500 hover:text-red-500 hover:bg-red-200 mt-0">Download</a>
    </div>
  </nav>
</template>
