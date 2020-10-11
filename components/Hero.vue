<template>
  <section class="text-gray-500 bg-gray-900 body-font flex-grow">
    <div
      class="container mx-auto flex px-5 py-8 md:py-24 md:flex-row flex-col items-center"
    >
      <div
        class="md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left md:mb-0 items-center text-center"
      >
        <!-- TITLE -->
        <h1 class="text-6xl text-white">
          <span class="font-hairline tracking-wider">FULLSTACK </span>
          <!-- <br class="hidden lg:inline-block" /> -->
          <span class="font-bold">ENGINEER</span>
        </h1>
        <!-- DESCRIPTION -->
        <p class="mb-8 leading-relaxed">
          I'm a 25-year-old systems engineer and passionate about technology,
          based in Buenos Aires. Not only I have experience in development and
          design systems but also in cloud computing, a little bit of BI and
          project management. I don't like the feeling of not knowing something.
          However, I like to use this feeling as a motor to continue growing
          professionally, learning new things, and improve day by day.
        </p>

        <div class="flex justify-center">
          <span
            class="inline-flex text-white bg-white border-0 py-1 px-6 rounded text-lg"
          >
          </span>
          <span
            class="ml-2 inline-flex text-gray-400 bg-blue-700 border-0 py-1 px-6 rounded text-lg"
          >
          </span>
          <span
            class="ml-2 inline-flex text-gray-400 bg-gray-800 border-0 py-1 px-6 rounded text-lg"
          >
          </span>
        </div>
        <SocialNetworks/>
      </div>
      <!-- IMAGEN -->
      <div
        class="flex md:order-none order-first justify-center h-auto lg:max-w-xl lg:w-full md:w-1/2 w-5/6"
      >
        <img
          class="h-56 md:h-92 rounded-full"
          src="../static/profile.jpg"
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
