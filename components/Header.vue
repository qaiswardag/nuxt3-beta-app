<template>
  <header>
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 border-b mb-8" aria-label="Top">
      <div class="w-full py-6 flex items-center justify-between lg:border-none">

        <NuxtLink to="/">
          <div class="flex-shrink-0 flex items-center">
            <h2 class="text-3xl sm:text-4xl">logo</h2>
          </div>
        </NuxtLink>

        <span class="sr-only">Workflow</span>

        <div class="flex items-center">
          <div class="hidden lg:block">
              <NuxtLink to="/" class="text-base font-medium hover:text-pink-600 text-center inline-block px-2">Home</NuxtLink>
              <NuxtLink to="/about" class="text-base font-medium hover:text-pink-600 text-center inline-block px-2">About</NuxtLink>
          </div>
        </div>
        <div class="ml-10 space-x-4">
          <NuxtLink to="#" class="inline-block bg-indigo-500 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-opacity-75">Sign in</NuxtLink>
          <NuxtLink to="#" class="inline-block bg-white py-2 px-4 border border-transparent rounded-md text-base font-medium text-indigo-600 hover:bg-indigo-50">Sign up</NuxtLink>
        </div>
      </div>
      <div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">


      </div>
    </nav>
  </header>
</template>
