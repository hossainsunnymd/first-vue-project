<script setup></script>

<template>
  <div class="p-5 lg:p-11 lg:rounded-r-2xl rounded-2xl">
    <h2 class="font-manrope text-4xl font-semibold leading-10 mb-11">
      Send Us A Message
    </h2>
    <input
      type="text"
      class="w-full h-12 text-gray-600 placeholder-gray-400 shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
      placeholder="Name"
    />
    <input
      type="text"
      class="w-full h-12 text-gray-600 placeholder-gray-400 shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
      placeholder="Email"
    />
    <input
      type="text"
      class="w-full h-12 text-gray-600 placeholder-gray-400 shadow-sm bg-transparent text-lg font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
      placeholder="Phone"
    />
    <textarea
      class="max-h-[200px] w-full text-gray-600 placeholder-gray-400 bg-transparent text-lg shadow-sm font-normal leading-7 border border-black focus:outline-none p-4 mb-10"
      placeholder="Message"
    ></textarea>
    <button
      class="w-full h-12 text-white text-base font-semibold leading-6 rounded-full transition-all duration-700 bg-black shadow-sm"
    >
      Send
    </button>
  </div>
</template>

<style scoped></style>
