<template>
  <div class="lg:hidden w-full h-20 bg-purple-300 fixed z-10 bottom-0 text-white">
    <div class="flex h-full text-center">
      <div class="bg-gray-900 w-full pt-4 border-r border-black shadow">
        <fa :icon="{prefix: 'fas', iconName: 'home'}" class="text-red-600 text-xl" />
        <p class="font-semibold">
          Home
        </p>
      </div>
      <div class="bg-gray-900 w-full pt-4 border-r border-black shadow">
        <fa :icon="{prefix: 'fas', iconName: 'cube'}" class="text-red-600 text-xl" />
        <p class="font-semibold">
          Blocks
        </p>
      </div>
      <div class="bg-gray-900 w-full pt-4 border-r border-black shadow">
        <fa :icon="{prefix: 'fas', iconName: 'plug'}" class="text-red-600 text-xl" />
        <p class="font-semibold">
          Components
        </p>
      </div>
      <div class="bg-gray-900 w-full pt-4 shadow">
        <fa :icon="{prefix: 'fab', iconName: 'github'}" class="text-red-600 text-xl" />
        <p class="font-semibold">
          Github
        </p>
      </div>
    </div>
  </div>
</template>
