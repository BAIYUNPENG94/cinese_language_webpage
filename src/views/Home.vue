<template>
  <Header />
  <Navbar />
  <div class="max-w-1200 mx-auto">
    <Carousel />
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

    <div style="height: 50px;"></div>

    <div class="flex flex-wrap max-w-1200 mx-auto">
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
      <div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/3 p-4">
        <div class="bg-gray-300 rounded-full w-40 h-40 mx-auto"></div>
        <div class="text-center">Description 1</div>
      </div>
    </div>

    <div style="height: 50px;"></div>

    <div class="bg-gray-100 rounded-lg p-6">
      <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div>
            <div class="bg-red-300 h-40"></div>
            <!-- <img :src="imageUrl" alt="图片" class="object-contain mx-auto max-w-full"> -->
          </div>
          <div>
            <h2 class="text-2xl font-bold mb-4">AAAAAAAAAAAA</h2>
            <p class="text-gray-600">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</p>
          </div>
        </div>
      </div>
    </div>
    <div style="height: 50px;"></div>
    <div class="bg-gray-100 rounded-lg p-6">
      <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div>
            <h2 class="text-2xl font-bold mb-4">AAAAAAAAAAAA</h2>
            <p class="text-gray-600">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</p>
          </div>
          <div>
            <div class="bg-red-300 h-40"></div>
            <!-- <img :src="imageUrl" alt="图片" class="object-contain mx-auto max-w-full"> -->
          </div>
        </div>
      </div>
    </div>


    <div style="height: 200px;"></div>

  </div>
  <Footer />
</template>

<script>
import Header from '/src/layouts/Header.vue';
import Footer from '/src/layouts/Footer.vue';
import Navbar from '/src/layouts/Navbar.vue';
import Carousel from '/src/components/Carousel.vue';

export default {
  components: {
    Header,
    Footer,
    Navbar,
    Carousel,
  }
}

</script>
