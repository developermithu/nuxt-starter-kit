<template>
<header class="text-gray-600 body-font shadow">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <NuxtLink to="/" class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-green-500 rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <span class="ml-3 text-xl"><span class="text-green-500">Nuxt</span>Kit</span>
    </NuxtLink>
    <nav class="md:ml-auto md:mr-auto flex flex-wrap items-center justify-center gap-x-5 text-lg">
      <NuxtLink to="/" class="hover:text-green-500">Home</NuxtLink>
      <NuxtLink to="/blog" class="hover:text-green-500 ">Blog</NuxtLink>
      <NuxtLink to="/price" class="hover:text-green-500">Price</NuxtLink>
      <NuxtLink to="/testimonial" class="hover:text-green-500">Testimonial</NuxtLink>
      <NuxtLink to="/contact" class="hover:text-green-500">Contact</NuxtLink>
    </nav>
    <button class="inline-flex items-center bg-gray-100 border-0 py-1.5 px-3 focus:outline-none hover:bg-green-500 hover:text-white rounded text-base">Login
      <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
        <path d="M5 12h14M12 5l7 7-7 7"></path>
      </svg>
    </button>
  </div>
</header>
</template>

<script>
export default {

}
</script>
