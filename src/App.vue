<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="min-h-screen bg-gray-100">
    <nav class="bg-white shadow-lg">
      <div class="max-w-7xl mx-auto px-4">
        <div class="flex justify-between h-16">
          <div class="flex">
            <div class="flex-shrink-0 flex items-center">
              <h1 class="text-xl font-bold text-gray-800">Dashboard</h1>
            </div>
            <div class="hidden md:block">
              <div class="ml-10 flex items-baseline space-x-4">
                <RouterLink to="/" class="text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Home</RouterLink>
                <RouterLink to="/about" class="text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">About</RouterLink>
                <RouterLink to="/contact" class="text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Contact</RouterLink>
                <RouterLink to="/profile" class="text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Profile</RouterLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <main class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
      <RouterView />
    </main>
  </div>
</template>

<style scoped>
</style>
