<template>
  <div class="min-h-screen bg-gray-50 flex flex-col items-center justify-center p-8">
    <div class="max-w-md w-full bg-white rounded-2xl shadow-lg p-8 text-center">
      <img 
        src="/avatar.png" 
        alt="My Avatar" 
        class="w-32 h-32 rounded-full mx-auto mb-4 border-4 border-blue-500 object-cover"
      />
      
      <h1 class="text-3xl font-bold text-gray-800 mb-2">Arnold Christian O. Calamba</h1>
      <p class="text-gray-600 mb-6">
        Welcome to my profile! I am a BSIT student at Caraga State University!
      </p>

      <nav class="flex justify-center gap-4">
        <NuxtLink 
          to="/profile" 
          class="px-6 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition-colors"
        >
          View My Profile
        </NuxtLink>
      </nav>
    </div>
  </div>
</template>