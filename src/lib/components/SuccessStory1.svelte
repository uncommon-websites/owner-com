<script lang="ts">
  // SuccessStory1 component
</script>

<section class="py-16 md:py-24">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-end mb-8">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-2">John & Sam</h2>
        <p class="text-xl md:text-2xl text-gray-600">Owners at Metro Pizza</p>
      </div>
      <button class="bg-black text-white px-6 py-3 rounded-lg font-medium hover:bg-gray-800 transition-colors hidden md:block">
        See all stories ›
      </button>
    </div>

    <div class="grid md:grid-cols-12 gap-8 bg-white rounded-3xl overflow-hidden">
      <!-- Left Content -->
      <div class="md:col-span-4 flex flex-col justify-between py-8">
        <blockquote class="text-lg text-gray-600 mb-12">
          "Owner is a must-have for succeeding online as an independent restaurant today"
        </blockquote>

        <div class="space-y-8">
          <div>
            <div class="text-4xl font-bold text-gray-900 mb-1">+54%</div>
            <div class="text-sm text-gray-500">Sales growth after switching to Owner</div>
          </div>
          <div>
            <div class="text-4xl font-bold text-gray-900 mb-1">11,000</div>
            <div class="text-sm text-gray-500">Installs of their own mobile app, created with Owner</div>
          </div>
        </div>
      </div>

      <!-- Right Image/Video -->
      <div class="md:col-span-8 relative h-[400px] md:h-[500px] rounded-3xl overflow-hidden group cursor-pointer">
        <img 
          src="https://images.unsplash.com/photo-1581349485608-9469926a8e5e?auto=format&fit=crop&q=80&w=1200" 
          alt="Metro Pizza Owners" 
          class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
        />
        <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
        
        <div class="absolute bottom-8 left-8 text-white">
          <p class="font-medium mb-1">See the story</p>
          <p class="text-2xl font-bold">Metro Pizza</p>
        </div>

        <div class="absolute bottom-8 right-8 w-12 h-12 bg-white rounded-full flex items-center justify-center pl-1 transition-transform group-hover:scale-110">
          <svg class="w-4 h-4 text-black" fill="currentColor" viewBox="0 0 24 24">
            <path d="M8 5v14l11-7z" />
          </svg>
        </div>
      </div>
    </div>

    <!-- Navigation -->
    <div class="flex justify-between items-center mt-8 border-t border-gray-200 pt-8">
      <button class="text-sm text-gray-500 hover:text-gray-900 flex items-center gap-2">
        <span class="w-8 h-8 rounded-full border border-gray-200 flex items-center justify-center">←</span>
        Previous <span class="font-medium">Don-Dali Diner</span>
      </button>
      <button class="text-sm text-gray-500 hover:text-gray-900 flex items-center gap-2">
        Next <span class="font-medium">Cyclo Noodles</span>
        <span class="w-8 h-8 rounded-full border border-gray-200 flex items-center justify-center">→</span>
      </button>
    </div>
  </div>
</section>
