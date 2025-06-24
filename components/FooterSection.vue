<template>
  <footer class="bg-white border-t">
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between">
        <div class="flex items-center space-x-2">
          <Icon name="heroicons:user-circle" class="w-6 h-6 text-blue-600" />
          <span class="text-gray-900 font-medium">Bo Clifton</span>
        </div>
        
        <div class="flex items-center space-x-6">
          <a 
            href="https://linkedin.com" 
            target="_blank" 
            rel="noopener noreferrer"
            class="text-gray-500 hover:text-gray-900 transition-colors"
            aria-label="LinkedIn"
          >
            <Icon name="simple-icons:linkedin" class="w-5 h-5" />
          </a>
          <a 
            href="https://github.com" 
            target="_blank" 
            rel="noopener noreferrer"
            class="text-gray-500 hover:text-gray-900 transition-colors"
            aria-label="GitHub"
          >
            <Icon name="simple-icons:github" class="w-5 h-5" />
          </a>
        </div>
      </div>
      
      <div class="mt-8 border-t pt-8">
        <p class="text-center text-sm text-gray-500">
          © {{ new Date().getFullYear() }} Bo Clifton. Software Developer & Architect.
        </p>
      </div>
    </div>
  </footer>
</template>

<script setup>
// Footer component for the main site footer
// Auto-imported by Nuxt - no need for manual registration
</script>
