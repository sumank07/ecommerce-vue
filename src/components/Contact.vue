<template>
  <div
    id="contact"
    class="min-h-screen scroll-mt-20 bg-pink-950 py-12 sm:px-6 lg:px-8"
  >
    <div class="max-w-7xl mx-auto">
      <div class="text-center mb-12">
        <h1 class="text-4xl font-bold font-serif text-white mb-4">
          Contact Us
        </h1>
        <p class="text-lg text-gray-200 max-w-2xl mx-auto">
          Have questions about our perfume? Our fragrance experts are here to
          help you.
        </p>
      </div>
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
        <div class="bg-white p-8 rounded-lg shadow-xl border border-gray-100">
          <h2 class="text-2xl font-serif font-semibold text-gray-900 mb-6">
            Send Us a Message
          </h2>

          <form class="space-y-6">
            <div>
              <label
                for="name"
                class="block text-sm font-medium text-gray-800 mb-1"
                >Your Name</label
              >
              <input
                type="text"
                id="name"
                class="w-full px-4 py-3 border-gray-200 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent"
                placeholder="Your name"
              />
            </div>

            <div>
              <label
                for="email"
                class="block text-sm font-medium text-gray-800 mb-1"
                >Email Address</label
              >
              <input
                type="text"
                id="email"
                class="w-full px-4 py-3 border-gray-200 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent"
                placeholder="Your@email.com"
              />
            </div>

            <div>
              <label
                for="message"
                class="block text-sm font-medium text-gray-800 mb-1"
                >Your Message</label
              >
              <textarea
                rows="5"
                id="message"
                class="w-full px-4 py-3 border-gray-200 rounded-lg focus:ring-2 focus:ring-pink-500 focus:border-transparent"
                placeholder="Tell us about your fragrance needs ..."
              ></textarea>
            </div>
            <button
              class="w-full bg-pink-700 hover:bg-pink-800 text-white py-3 px-6 rounded-lg trasition duration-300 font-medium shadow-md"
            >
              Send Messsage
            </button>
          </form>
        </div>

        <div class="space-y-8">
          <div class="bg-white p-8 rounded-lg shadow-xl border border-gray-100">
            <h2 class="text-2xl font-semibold font-serif text-gray-900 mb-6">
              Contact Informations
            </h2>

            <div class="space-y-6">
              <div class="flex items-start">
                <div class="bg-pink-200 p-3 rounded-full mr-4">
                  <Icon icon="fa-solid:phone" class="text-pink-950 text-lg" />
                </div>
                <div>
                  <h3 class="text-lg font-medium text-gray-900">Phone</h3>
                  <p class="text-gray-800">+1 (236) 567-8900</p>
                  <p class="text-gray-600">Mon-Fri:10am-6pm</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="bg-pink-200 p-3 rounded-full mr-4">
                  <Icon
                    icon="fa-solid:map-marker-alt"
                    class="text-pink-950 text-lg"
                  />
                </div>
                <div>
                  <h3 class="text-lg font-medium text-gray-900">Email</h3>
                  <p class="text-gray-800">contact@perfumeslux.com</p>
                  <p class="text-gray-600">support@perfumeslux.com</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="bg-pink-200 p-3 rounded-full mr-4">
                  <Icon
                    icon="fa-solid:map-marker-alt"
                    class="text-pink-950 text-lg"
                  />
                </div>
                <div>
                  <h3 class="text-lg font-medium text-gray-900">
                    Our Bautique
                  </h3>
                  <p class="text-gray-800">123 Perfume Street</p>
                  <p class="text-gray-600">Paris, France 75001</p>
                </div>
              </div>
            </div>

            <div class="mt-24">
              <h3 class="text-lg font-medium text-gray-900 mb-4">Follow Us</h3>
              <div class="flex space-x-4">
                <a
                  href="#"
                  class="bg-pink-200 hover:bg-gray-200 p-3 rounded-full transition duration-300"
                >
                  <Icon icon="fa-brands:instagram" class="text-pink-950" />
                </a>
                <a
                  href="#"
                  class="bg-pink-200 hover:bg-gray-200 p-3 rounded-full transition duration-300"
                >
                  <Icon icon="fa-brands:facebook-f" class="text-pink-950" />
                </a>
                <a
                  href="#"
                  class="bg-pink-200 hover:bg-gray-200 p-3 rounded-full transition duration-300"
                >
                  <Icon icon="fa-brands:twitter" class="text-pink-950" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
