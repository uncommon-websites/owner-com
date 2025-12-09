<script lang="ts">
  // Header component
</script>

<header class="sticky top-0 z-50 w-full bg-[#FBFBF9]/80 backdrop-blur-md border-b border-gray-200/50">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
    <!-- Logo -->
    <div class="flex items-center gap-2">
      <a href="/" class="flex items-center gap-2 text-xl font-bold tracking-tight text-gray-900">
        <div class="w-6 h-6 rounded-full border-2 border-gray-900 flex items-center justify-center">
          <div class="w-2 h-2 bg-gray-900 rounded-full"></div>
        </div>
        Owner
      </a>
    </div>

    <!-- Navigation -->
    <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#" class="hover:text-gray-900 transition-colors">Product</a>
      <a href="#" class="hover:text-gray-900 transition-colors">Pricing</a>
      <a href="#" class="hover:text-gray-900 transition-colors">How it works</a>
      <a href="#" class="hover:text-gray-900 transition-colors">Company</a>
      <a href="#" class="hover:text-gray-900 transition-colors">Resources</a>
    </nav>

    <!-- Actions -->
    <div class="flex items-center gap-4">
      <a href="#" class="text-sm font-medium text-gray-900 hover:text-gray-700">Login</a>
      <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white text-sm font-medium px-4 py-2 rounded-lg transition-colors shadow-sm">
        Get a free demo
      </a>
    </div>
  </div>
</header>
