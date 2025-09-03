<template>
  <div
    id="about"
    class="min-h-screen scroll-mt-20 bg-gradient-to-b from-gray-50 to-white py-12 px-4 sm:px-6 lg:px-8"
  >
    <div class="max-w-7xl mx-auto">
      <div class="flex flex-col lg:flex-row gap-12 mb-20">
        <div class="lg:w-1/2">
          <div class="relative rounded-2xl overflow-hidden h-96 shadow-xl">
            <img
              :src="productImg0"
              alt="Luxury Perfumes"
              class="w-full h-full object-cover"
            />
            <div
              class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-50"
            ></div>
            <div class="absolute bottom-0 left-0 p-6 text-white">
              <h3 class="text-2xl font-bold">Since 2021</h3>
              <p class="mt-2">Crafting perfumes with passion</p>
            </div>
          </div>
        </div>

        <div class="lg:w-1/2 flex-col justify-center">
          <h2 class="text-4xl font-bold text-amber-900 mb-6">About Us</h2>
          <p class="text-lg text-gray-600 mb-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam,
            perferendis laudantium cum maxime eos numquam laboriosam illo
            excepturi perspiciatis maiores recusandae accusantium necessitatibus
            consequatur. Hic harum quia in beatae culpa.
          </p>
          <div class="grid grid-cols-2 gap-4 mt-4">
            <div
              class="bg-white p-4 rounded-lg shadow-sm border border-gray-100"
            >
              <h4 class="font-semibold text-pink-600 text-xl">500+</h4>
              <p class="text-gray-600">Unique Fragrances</p>
            </div>

            <div
              class="bg-white p-4 rounded-lg shadow-sm border border-gray-100"
            >
              <h4 class="font-semibold text-blue-600 text-xl">2000+</h4>
              <p class="text-gray-600">Happy Customers</p>
            </div>

            <div
              class="bg-white p-4 rounded-lg shadow-sm border border-gray-100"
            >
              <h4 class="font-semibold text-amber-600 text-xl">50+</h4>
              <p class="text-gray-600">Countries worldwide</p>
            </div>
            <div
              class="bg-white p-4 rounded-lg shadow-sm border border-gray-100"
            >
              <h4 class="font-semibold text-amber-600 text-xl">24/7</h4>
              <p class="text-gray-600">Customer Support</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>

import productImg0 from "../assets/product.png";
</script>
