<template>
  <div class="p-6">
    <h1 class="text-3xl font-bold mb-4">Profile</h1>
    <p class="text-gray-700 mb-6">Manage your profile settings here.</p>
    
    <div class="max-w-2xl mx-auto">
      <div class="bg-white rounded-lg shadow-md p-6">
        <div class="flex items-center mb-6">
          <img src="https://via.placeholder.com/100" alt="Profile Picture" class="w-20 h-20 rounded-full mr-6">
          <div>
            <h2 class="text-2xl font-bold text-gray-900">John Doe</h2>
            <p class="text-gray-600">Dashboard User</p>
          </div>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div>
            <h3 class="text-lg font-semibold mb-3">Personal Information</h3>
            <div class="space-y-3">
              <div>
                <label class="block text-sm font-medium text-gray-700">Name</label>
                <p class="text-gray-900">John Doe</p>
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700">Address</label>
                <p class="text-gray-900">123 Main Street<br>Anytown, ST 12345</p>
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700">Height</label>
                <p class="text-gray-900">5'10" (178 cm)</p>
              </div>
            </div>
          </div>
          
          <div>
            <h3 class="text-lg font-semibold mb-3">Preferences</h3>
            <div class="space-y-3">
              <div>
                <label class="block text-sm font-medium text-gray-700">Favorite Color</label>
                <p class="text-gray-900">Blue</p>
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700">Favorite Food</label>
                <p class="text-gray-900">Pizza</p>
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700">Habit</label>
                <p class="text-gray-900">Reading books every evening</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Profile'
}
</script>