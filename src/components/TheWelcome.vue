<template>
  <section class="py-16 px-4 sm:px-8 lg:px-16 bg-gray-700 mb-2">
    <div class="max-w-6xl mx-auto flex flex-col sm:flex-row items-center justify-center space-y-8 sm:space-y-0">
    
      <div
        class="w-60 h-60 sm:w-72 sm:h-72 rounded-full border-4 border-white shadow-lg shadow-sky-400 overflow-hidden flex-shrink-0 sm:mr-8 mb-8 sm:mb-0">
        <img src="/s.jpg" alt="Profile Image" class="w-full h-full object-cover" />
      </div>

    
      <div class="text-center sm:text-left">
        <h1 class="text-4xl font-extrabold font-serif mb-4 text-white">
          Serwin Torijos
        </h1>
        <p class="text-xl mb-4 font-semibold text-white">BSIT 3D</p>
        <p class="text-xl mb-8 font-semibold text-white">
          Web Developer and Programmer
        </p>

      
        <div>
          <div class="flex justify-center sm:justify-start space-x-4 mt-4">
         
            <a href="https://github.com/yourprofile" target="_blank"
              class="text-rose-600 hover:text-rose-800 transition-colors">
              <i class="fab fa-github fa-2x"></i>
            </a>

            <a href="https://facebook.com/yourprofile" target="_blank"
              class="text-blue-500 hover:text-blue-700 transition-colors">
              <i class="fab fa-facebook fa-2x"></i>
            </a>

            <!-- Instagram -->
            <a href="https://instagram.com/yourprofile" target="_blank"
              class="text-yellow-400 hover:text-yellow-600 transition-colors">
              <i class="fab fa-instagram fa-2x"></i>
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Major Subjects Section -->
  <section class="py-16 px-4 sm:px-8 lg:px-16 bg-gray-800 mb-2">
    <h1 class="text-4xl font-bold mb-12 text-center text-white">
      Choice of major subjects
    </h1>
    <div class="max-w-6xl mx-auto grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <div class="group bg-white rounded-lg overflow-hidden shadow-lg shadow-sky-400 transition transform hover:scale-105">
        <img src="/intro.png" alt="Project 1" class="w-full h-56 object-cover" />
        <div class="p-6">
          <h2 class="text-lg font-semibold mb-2">1st Year</h2>
          <p class="text-gray-600">Introduction to Programming</p>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="group bg-white rounded-lg overflow-hidden shadow-sky-400 shadow-lg transition transform hover:scale-105">
        <img src="/net.jpg" alt="Project 2" class="w-full h-56 object-cover" />
        <div class="p-6">
          <h2 class="text-lg font-semibold mb-2">2nd Year</h2>
          <p class="text-gray-600">Networking</p>
        </div>
      </div>

      <!-- Card 3 -->
      <div class="group bg-white rounded-lg overflow-hidden shadow-sky-400 shadow-lg transition transform hover:scale-105">
        <img src="/app.png" alt="Project 3" class="w-full h-56 object-cover" />
        <div class="p-6">
          <h2 class="text-lg font-semibold mb-2">3rd Year</h2>
          <p class="text-gray-600">App Development</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="py-16 px-4 sm:px-8 lg:px-16 bg-gray-700 mb-2">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl font-extrabold text-white mb-8 text-center">
        Information
      </h2>
      <!-- Card Container -->
      <div class="bg-white p-6 rounded-xl shadow-lg">
        <form class="space-y-6">
          <!-- Email -->
          <div>
            <label for="email" class="block text-gray-700 text-lg mb-2 font-serif font-semibold">
              Email:
            </label>
            <div class="bg-gray-100 py-4 px-6 rounded-xl shadow-inner text-center">
              <h1 class="font-semibold text-gray-700">
                sherwintorrejos1@gmail.com
              </h1>
            </div>
          </div>
          <!-- Phone Number -->
          <div>
            <label for="phone" class="block text-gray-700 text-lg mb-2 font-serif font-semibold">
              Phone Number:
            </label>
            <div class="bg-gray-100 py-4 px-6 rounded-xl shadow-inner text-center">
              <h1 class="font-semibold text-gray-700">09482188106</h1>
            </div>
          </div>
          <!-- Status -->
          <div>
            <label for="status" class="block text-gray-700 text-lg mb-2 font-serif font-semibold">
              Status:
            </label>
            <div class="bg-gray-100 py-4 px-6 rounded-xl shadow-inner text-center ">
              <h1 class="font-semibold text-gray-700">Single</h1>
            </div>
          </div>
          <!-- Nationality -->
          <div>
            <label for="nationality" class="block text-gray-700 text-lg mb-2 font-serif font-semibold">
              Nationality:
            </label>
            <div class="bg-gray-100 py-4 px-6 rounded-xl shadow-inner text-center">
              <h1 class="font-semibold text-gray-700">Filipino</h1>
            </div>
          </div>
        </form>
      </div>
    </div>
  </section>

</template>

<script>
export default {};
</script>
