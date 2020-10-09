<template>
  <section class="text-gray-500 bg-gray-900 body-font flex-grow">
    <div
      class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
    >
      <div
        class="md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
      >
        <h1 class="font-5xl sm:text-4xl mb-4 text-white tracking-wider">
          <span class="font-hairline">FULLSTACK </span>
          <br class="hidden lg:inline-block" />
          <span class="font-black">ENGINEER</span>
        </h1>
        <p class="mb-8 leading-relaxed">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium minima sit facilis temporibus expedita, eius atque quam cupiditate, neque ipsam adipisci veniam doloribus nemo, qui repellat magnam soluta sapiente quidem. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda sequi veritatis soluta excepturi perferendis ut error! Fugit, autem! Maxime fugit voluptate vel minima cum cumque dolorum quas tenetur rerum nam.
        </p>
        <div class="flex justify-center">
          <button
            class="inline-flex text-white bg-white border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg"
          >
          </button>
          <button
            class="ml-4 inline-flex text-gray-400 bg-blue-700 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg"
          >
          </button>
          <button
            class="ml-4 inline-flex text-gray-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg"
          >
          </button>
        </div>
      </div>
      <div class="flex justify-center h-45 lg:max-w-xl lg:w-full md:w-1/2 w-5/6">
        <img
          class="object-contain object-center rounded"
          src="../static/logotipo.svg"
          alt="amilcarrey logotipo"
        />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>
