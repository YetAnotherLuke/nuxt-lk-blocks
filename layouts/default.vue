<template>
  <main class="bg-gray-200 antialiased relative">
    <Header class="shadow" />
    <div class="flex h-screen">
      <div class="hidden lg:block w-12 hover:w-56 bg-gray-900 transition-all-half overflow-hidden pt-2 pl-3">
        <div class="flex items-center flex-shrink-0 text-white py-3">
          <div class="absolute">
            <fa :icon="{prefix: 'fas', iconName: 'home'}" class="text-red-600 text-xl" />
          </div>
          <span class="text-gray-100 relative overflow-hidden pl-10">Home</span>
        </div>
        <div class="flex items-center flex-shrink-0 text-white py-3">
          <div class="absolute">
            <fa :icon="{prefix: 'fas', iconName: 'stream'}" class="text-red-600 text-xl" />
          </div>
          <span class="text-gray-100 relative overflow-hidden pl-10">Blocks</span>
        </div>
        <div class="flex items-center flex-shrink-0 text-white py-3">
          <div class="absolute">
            <fa :icon="{prefix: 'fas', iconName: 'heart'}" class="text-red-600 text-xl" />
          </div>
          <span class="text-gray-100 relative overflow-hidden pl-10">Components</span>
        </div>
      </div>
      <nuxt class="w-full m-5 md:m-10" />
    </div>
    <MobileNav />
  </main>
</template>

<script>
import Header from '~/components/layout/Header.vue'
import MobileNav from '~/components/layout/MobileNav.vue'
export default {
  components: {
    Header,
    MobileNav
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
