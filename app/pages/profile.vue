
<template>
  <div class="min-h-screen bg-orange-200 py-12 px-4 sm:px-6 lg:px-8">
    <div class="max-w-3xl mx-auto space-y-8">

      <div class="flex items-center justify-between">
        <h1 class="text-3xl font-bold text-gray-900">My Profile</h1>
        <NuxtLink 
          to="/" 
          class="px-4 py-2 bg-amber-200 text-gray-800 rounded-lg hover:bg-gray-300 transition-colors"
        >
          ← Back to Home
        </NuxtLink>
      </div>
    
      <div class="bg-amber-100 shadow rounded-2xl p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4 border-b pb-2">Personal Info</h2>
        <ul class="space-y-2 text-gray-700">
          <li><strong>Name:</strong> Arnold Christian O. Calamba</li>
          <li><strong>Location:</strong> Brgy. Villa Kananga, Butuan City</li>
          <li><strong>Email:</strong> matchstick173@gmail.com</li>
        </ul>
      </div>

      <div class="bg-amber-100 shadow rounded-2xl p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4 border-b pb-2">Educational Background</h2>
        <div class="space-y-4">
          <div>
            <h3 class="font-medium text-gray-800">Bachelor of Science in Information Technology Student</h3>
            <p class="text-gray-600">Caraga State University, 2020 - 2026</p>
          </div>
          <div>
            <h3 class="font-medium text-gray-800">Frontend Development</h3>
            <p class="text-gray-600">Sololearn, 2023</p>
          </div>
        </div>
      </div>

      <div class="bg-amber-100 shadow rounded-2xl p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4 border-b pb-2">Skills & Interests</h2>
        <div class="flex flex-wrap gap-2">
          <span class="px-3 py-1 bg-orange-100 text-orange-800 rounded-full text-sm font-medium">JavaScript</span>
          <span class="px-3 py-1 bg-green-200 text-green-900 rounded-full text-sm font-medium">Vue.js</span>
          <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm font-medium">Nuxt</span>
          <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm font-medium">Tailwind CSS</span>
          <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm font-medium">UI/UX Design</span>
          <span class="px-3 py-1 bg-gray-400 text-gray-800 rounded-full text-sm font-medium">Backend Development</span>
          <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-sm font-medium">Writing</span>
        </div>
      </div>

      <div class="bg-amber-100 shadow rounded-2xl p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4 border-b pb-2">Hobbies</h2>
        <ul class="list-disc list-inside text-gray-700 space-y-1">
          <li>Staying home and writing fiction</li>
          <li>Reading and watching fiction</li>
          <li>Enjoying video games</li>
          <li>Working on minor projects involving writing</li>
        </ul>
      </div>
    </div>
  </div>
</template>