<script setup></script>

<template>
  <!-- https://picsum.photos/id/237/200/300 -->
  <div class="bg-secondary dark:bg-darkBg text-gray-800 dark:text-darkText px-[3rem]">
    <div class="max-w-1280 mx-auto px-4">
      <!-- Hero Section -->
      <section class="flex flex-col md:flex-row items-center py-12">
        <div class="md:w-1/2 text-center md:text-left">
          <h1 class="text-4xl font-bold mb-4">
            Stress less with simple pricing and pixel-perfect photo edits
          </h1>
          <p class="text-lg">Discover affordable photo editing rates tailored to your needs.</p>
        </div>
        <div class="md:w-1/2 flex justify-center">
          <img src="https://via.placeholder.com/400x300" alt="Hero Image" class="rounded" />
        </div>
      </section>

      <!-- Pricing Section -->
      <section>
        <h2 class="text-center text-3xl md:text-4xl font-bold text-primary mb-8">
          See the starting cost for photo editing rates
        </h2>
        <p class="text-center text-lg md:text-xl mb-6">
          Photo editing is essential for creating visually appealing images, whether for personal or
          professional use. Here's a quick guide to help you understand starting rates.
        </p>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
          <!-- Card -->
          <div class="bg-white dark:bg-gray-800 shadow rounded-lg p-4">
            <img
              src="https://via.placeholder.com/300x200"
              alt="Clipping Path"
              class="rounded mb-4"
            />
            <h3 class="text-xl font-bold mb-2">Clipping Path</h3>
            <p class="mb-4">Hand-drawn clipping paths give you crisp, clean cutouts.</p>
            <p class="text-primary font-bold">Starting at $0.39 per image</p>
            <a
              href="#"
              class="block text-center mt-4 bg-primary text-white py-2 rounded hover:bg-yellow-600"
              >View Details</a
            >
          </div>
          <!-- Repeat similar cards for other services -->
          <div class="bg-white dark:bg-gray-800 shadow rounded-lg p-4">
            <img
              src="https://via.placeholder.com/300x200"
              alt="Skin Retouch"
              class="rounded mb-4"
            />
            <h3 class="text-xl font-bold mb-2">Skin Retouch</h3>
            <p class="mb-4">Enhance your images with professional skin retouching.</p>
            <p class="text-primary font-bold">Starting at $0.39 per image</p>
            <a
              href="#"
              class="block text-center mt-4 bg-primary text-white py-2 rounded hover:bg-yellow-600"
              >View Details</a
            >
          </div>
          <div class="bg-white dark:bg-gray-800 shadow rounded-lg p-4">
            <img
              src="https://via.placeholder.com/300x200"
              alt="Jewelry Path"
              class="rounded mb-4"
            />
            <h3 class="text-xl font-bold mb-2">Jewelry Path</h3>
            <p class="mb-4">Perfect edits for jewelry images with precision cutouts.</p>
            <p class="text-primary font-bold">Starting at $0.39 per image</p>
            <a
              href="#"
              class="block text-center mt-4 bg-primary text-white py-2 rounded hover:bg-yellow-600"
              >View Details</a
            >
          </div>
        </div>
      </section>

      <!-- FAQ Section -->
      <section class="py-12">
        <h2 class="text-2xl font-bold mb-6">Payment Information for HRS Edit Services</h2>
        <div class="space-y-4">
          <details class="bg-gray-100 dark:bg-gray-800 rounded p-4">
            <summary class="font-bold cursor-pointer">What services do you offer?</summary>
            <p class="mt-2">We offer clipping paths, retouching, jewelry edits, and more.</p>
          </details>
          <details class="bg-gray-100 dark:bg-gray-800 rounded p-4">
            <summary class="font-bold cursor-pointer">How do I submit my photos?</summary>
            <p class="mt-2">You can upload your photos through our secure portal.</p>
          </details>
          <!-- Add more FAQ items -->
        </div>
      </section>

      <!-- Payment Section -->
      <section class="py-12 text-center">
        <div class="flex justify-center mb-4">
          <div class="bg-green-500 text-white rounded-full p-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-12 w-12"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9 12l2 2 4-4m7 2a9 9 0 11-18 0 9 9 0 0118 0z"
              />
            </svg>
          </div>
        </div>
        <h2 class="text-2xl font-bold mb-4">Fast, secure checkout</h2>
        <p>We accept major credit cards and PayPal.</p>
        <div class="flex justify-center space-x-4 mt-4">
          <img src="https://via.placeholder.com/50x30" alt="Visa" />
          <img src="https://via.placeholder.com/50x30" alt="MasterCard" />
          <img src="https://via.placeholder.com/50x30" alt="Payoneer" />
          <img src="https://via.placeholder.com/50x30" alt="PayPal" />
        </div>
      </section>
    </div>
  </div>
</template>
