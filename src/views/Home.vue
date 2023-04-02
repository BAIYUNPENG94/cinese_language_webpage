<template>
  <Header/>
  <Navbar/>
  <div class="max-w-1200 mx-auto">
    <div class="flex flex-wrap max-w-1200 mx-auto">
      <div class="w-full ">
        <div class="bg-gray-300 h-32"></div>
      </div>
      <div class="w-full ">
        <div class="bg-gray-400 h-32"></div>
      </div>
      <div class="w-full ">
        <div class="bg-gray-500 h-32"></div>
      </div>
      <div class="w-full ">
        <div class="bg-gray-600 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-300 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-400 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-500 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-600 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-700 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-800 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-gray-900 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-red-300 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-red-400 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-red-500 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-red-600 h-32"></div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4">
        <div class="bg-red-700 h-32"></div>
      </div>
    </div>
  </div>
  <Footer/>
</template>

<script>
import Header from '/src/layouts/Header.vue';
import Footer from '/src/layouts/Footer.vue';
import Navbar from '/src/layouts/Navbar.vue';

export default {
  components: {
    Header,
    Footer,
    Navbar,
  }
}

</script>
