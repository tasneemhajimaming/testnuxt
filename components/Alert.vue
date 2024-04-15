<template>
   <nav class="bg-white py-6 text-[25px]">
    <div class="container mx-auto flex justify-between ">
      <div class="text-gray text-lg">Logo</div>
      <div class="text-gray cursor-pointer">
        <NuxtLink to="/dashboard" class="hover:text-red-500">Home</NuxtLink>
        <NuxtLink to="/shop" class="hover:text-red-500 ml-4">Shop</NuxtLink>
        <a to="/contact" class="hover:text-red-500 ml-4">Pages</a>
        <a to="/contact" class="hover:text-red-500 ml-4">Blog</a>
        <a to="/contact" class="hover:text-red-500 ml-4">Contact</a>
      </div>
      <div>
        <NuxtLink to="/index" class="text-cyan-300">Login Here</NuxtLink>
      </div>
    </div>
  </nav>
</template>