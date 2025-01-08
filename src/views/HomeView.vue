<script setup>
const items = [1, 2, 3, 2]
</script>

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
          <div
            v-for="(item, index) in items"
            :key="index"
            class="max-w-sm mx-auto rounded-lg overflow-hidden shadow-md bg-white dark:bg-gray-800"
          >
            <!-- Full-width image -->
            <div class="relative">
              <img
                src="https://via.placeholder.com/300x200"
                alt="Product Image"
                class="w-full h-48 object-cover"
              />
            </div>

            <div
              class="bg-white border rounded-md p-4 shadow-md max-w-sm flex justify-between items-start"
            >
              <div>
                <h2 class="text-yellow-500 text-xl font-semibold mb-2">Skin Retouch</h2>
                <p class="text-gray-600">
                  Hand-drawn clipping paths give you crisp, clean cutouts that you can put on any
                  background.
                </p>
              </div>
              <div class="bg-yellow-100 text-yellow-700 text-sm font-medium rounded-md px-3 py-2">
                Starting at <span class="font-bold">$0.39</span> per image
              </div>
            </div>

            <!-- Full-width button -->
            <button
              class="w-full px-4 py-3 bg-yellow-500 hover:bg-yellow-600 text-white font-semibold text-center"
            >
              View details
            </button>
          </div>
        </div>
      </section>

      <!-- FAQ Section -->
      <section class="py-12">
        <div class="flex flex-col md:flex-row items-start md:items-center gap-8 p-6 bg-gray-50">
          <!-- FAQ Section -->
          <div class="w-full md:w-1/2">
            <div class="space-y-4">
              <!-- Accordion Item -->
              <div class="border rounded-lg shadow-sm bg-white">
                <button
                  class="w-full text-left p-4 text-gray-700 font-semibold flex justify-between items-center"
                >
                  What Services Do You Offer?
                  <span class="text-gray-500">+</span>
                </button>
              </div>
              <!-- Accordion Item -->
              <div class="border rounded-lg shadow-sm bg-white">
                <button
                  class="w-full text-left p-4 text-gray-700 font-semibold flex justify-between items-center"
                >
                  How Do I Submit My Photos?
                  <span class="text-gray-500">+</span>
                </button>
              </div>
              <!-- Accordion Item -->
              <div class="border rounded-lg shadow-sm bg-white">
                <button
                  class="w-full text-left p-4 text-gray-700 font-semibold flex justify-between items-center"
                >
                  What Are Your Prices and Turnaround Times?
                  <span class="text-gray-500">+</span>
                </button>
              </div>
              <!-- Accordion Item -->
              <div class="border rounded-lg shadow-sm bg-white">
                <button
                  class="w-full text-left p-4 text-gray-700 font-semibold flex justify-between items-center"
                >
                  Do You Offer Revisions and Privacy Protection?
                  <span class="text-gray-500">+</span>
                </button>
              </div>
              <!-- Accordion Item -->
              <div class="border rounded-lg shadow-sm bg-white">
                <button
                  class="w-full text-left p-4 text-gray-700 font-semibold flex justify-between items-center"
                >
                  How Can I Get Started or Contact You?
                  <span class="text-gray-500">+</span>
                </button>
              </div>
            </div>
          </div>

          <!-- Illustration Section -->
          <div class="w-full md:w-1/2 flex justify-center">
            <img
              src="https://cdn.pixabay.com/photo/2019/01/18/20/08/heart-3940561_640.jpg "
              alt="Illustration"
              class="w-full max-w-md"
            />
          </div>
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
