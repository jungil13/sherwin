<template>
  <div class="min-h-screen flex flex-col">
    <!-- Header -->
    <header class="bg-gray-800 text-white mb-2">
      <div class="container mx-auto px-4">
        <nav class="flex items-center justify-between py-4">
          <div class="flex items-center">
            <h1 class="text-white text-lg font-semibold cursor-pointer">S H E R W I N</h1>
          </div>
        </nav>
      </div>
    </header>

    <!-- Main Content -->
    <main class="flex-1">
      <RouterView />
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
      <div class="container mx-auto px-4 text-center">
        <p>&copy; 2024 My CV. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
</script>

<style scoped>
/* Optional: Add additional scoped styles here */
</style>
