<template>
  <div>
    <header class="bg-blue-600 text-white text-center py-20">
      <h1 class="text-4xl font-bold">Welcome to Kaiser Klowns</h1>
      <p class="mt-4">Experience the joy and thrill of our unique clown brand!</p>
      <button class="mt-6 bg-yellow-500 text-black py-2 px-4 rounded hover:bg-yellow-400">
        Discover More
      </button>
    </header>

    <section class="py-16 px-4">
      <h2 class="text-2xl font-bold text-center mb-8">Our Products</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white rounded-lg shadow-lg p-4">
          <img src="path/to/image1.jpg" alt="Product 1" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-lg font-semibold mt-2">Product 1</h3>
          <p class="mt-1">Description of product 1.</p>
        </div>
        <div class="bg-white rounded-lg shadow-lg p-4">
          <img src="path/to/image2.jpg" alt="Product 2" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-lg font-semibold mt-2">Product 2</h3>
          <p class="mt-1">Description of product 2.</p>
        </div>
        <div class="bg-white rounded-lg shadow-lg p-4">
          <img src="path/to/image3.jpg" alt="Product 3" class="w-full h-48 object-cover rounded-t-lg">
          <h3 class="text-lg font-semibold mt-2">Product 3</h3>
          <p class="mt-1">Description of product 3.</p>
        </div>
      </div>
    </section>

    <footer class="bg-black text-white text-center py-4">
      <p>&copy; 2024 Kaiser Klowns. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style scoped>
/* สามารถใส่สไตล์เพิ่มเติมได้ที่นี่ */
</style>
