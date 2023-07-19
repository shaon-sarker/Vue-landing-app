<template lang="">
  <section class="text-gray-600 body-font bg-blue-700">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-zinc-50">{{ herosection.heading1 }} 
        <br class="hidden lg:inline-block">{{ herosection.heading2 }} 
      </h1>
      <p class="mb-8 leading-relaxed text-zinc-50">{{ herosection.paragraph }}</p>
      <div class="flex justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">{{ herosection.button1 }}</button>
        <button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">{{ herosection.button2 }}</button>
      </div>
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
      <img class="object-cover object-center rounded" alt="hero" :src="herosection.imageUrl">
    </div>
  </div>
</section>
</template>

<script setup>
    const herosection = {
      imageUrl: '/hero-img.png',
      heading1: 'Promote Your Products',
      heading2: 'by Techweb',
      paragraph: 'Another cool free html css template by Colorlib Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast',
      button1:'See features',
      button2:'Pricing',
    }
</script>