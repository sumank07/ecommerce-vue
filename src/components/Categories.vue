<template>
  <section id="categories" class="py-16 scroll-mt-20 bg-white">
    <div class="container mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-amber-950 mb-3">
          Explore Our Fragrance Collection
        </h2>
        <p class="text-lg text-gray-800 max-w-2xl mx-auto">
          Discover scents that match your personality.
        </p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-3 lg:grid-cols-3 gap-6">
        <div
          v-for="(category, index) in categories"
          :key="index"
          class="relative group overflow-hidden rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300"
        >
          <!-- Image -->
          <div class="h-64 overflow-hidden">
            <img
              :src="category.image"
              :alt="category.alt"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
            />
          </div>

          <!-- Overlay -->
          <div
            class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"
          >
            <div class="absolute bottom-0 left-0 p-6">
              <h3 class="text-xl font-semibold text-white">
                {{ category.title }}
              </h3>
              <p class="text-gray-200 mt-1">{{ category.description }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";
import productImg8 from "../assets/product8.png";
import productImg9 from "../assets/product9.png";
import productImg10 from "../assets/product10.png";
import productImg11 from "../assets/product11.png";
import productImg12 from "../assets/product12.png";
import productImg13 from "../assets/product122.png";

const categories = ref([
  {
    image: productImg8,
    title: "Men's Collection",
    description: "Bold & masculine scents",
    alt: "Men's perfume collection bold masculine scents",
  },
  {
    image: productImg9,
    title: "Women's Collection",
    description: "Elegant & feminine aromas",
    alt: "Women's perfume collection elegant feminine aromas",
  },
  {
    image: productImg10,
    title: "Men's Collection",
    description: "Fresh & confident fragrance",
    alt: "Men's perfume collection fresh confident fragrance",
  },
  {
    image: productImg11,
    title: "Women's Collection",
    description: "Graceful & timeless essence",
    alt: "Women's perfume collection graceful timeless essence",
  },
  {
    image: productImg12,
    title: "Men's Collection",
    description: "Powerful & modern notes",
    alt: "Men's perfume collection powerful modern notes",
  },
  {
    image: productImg13,
    title: "Women's Collection",
    description: "Delicate & enchanting scents",
    alt: "Women's perfume collection delicate enchanting scents",
  },
]);
</script>
