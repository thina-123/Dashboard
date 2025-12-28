<template>
  <div class="p-6">
    <h1 class="text-3xl font-bold mb-4">Contact</h1>
    <p class="text-gray-700 mb-6">Get in touch with us on the Contact page.</p>
    
    <div class="max-w-2xl mx-auto">
      <div class="bg-white rounded-lg shadow-md p-6">
        <h2 class="text-xl font-semibold mb-4">Contact Information</h2>
        <div class="space-y-4">
          <div class="flex items-center">
            <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center mr-4">
              <svg class="w-4 h-4 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
              </svg>
            </div>
            <div>
              <p class="font-medium">Email</p>
              <p class="text-gray-600">contact@dashboard.com</p>
            </div>
          </div>
          
          <div class="flex items-center">
            <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center mr-4">
              <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
              </svg>
            </div>
            <div>
              <p class="font-medium">Phone</p>
              <p class="text-gray-600">+1 (555) 123-4567</p>
            </div>
          </div>
          
          <div class="flex items-center">
            <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center mr-4">
              <svg class="w-4 h-4 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
              </svg>
            </div>
            <div>
              <p class="font-medium">Address</p>
              <p class="text-gray-600">123 Dashboard Street<br>Tech City, TC 12345</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>