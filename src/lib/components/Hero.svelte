<script lang="ts">
  // Hero component
</script>

<section class="pt-20 pb-16 md:pt-32 md:pb-24 overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <div class="inline-flex items-center gap-1 text-sm text-gray-500 mb-6">
      <span class="font-medium text-gray-900">#1 Top-Rated Restaurant Software</span>
      <span>4.8</span>
      <span class="text-yellow-400">★</span>
      <span>across 550+ reviews</span>
    </div>

    <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 mb-6 max-w-4xl mx-auto leading-[1.1]">
      You're losing sales online. <br class="hidden md:block" />
      Use AI to see what to fix.
    </h1>

    <div class="relative mt-12 md:mt-16 max-w-[320px] mx-auto">
      <!-- Phone Frame -->
      <div class="relative z-10 bg-black rounded-[40px] p-3 shadow-2xl border-[6px] border-gray-800">
        <div class="bg-white rounded-[32px] overflow-hidden h-[600px] relative">
          <!-- Status Bar -->
          <div class="h-12 flex justify-between items-center px-6 pt-2">
            <span class="text-xs font-semibold">9:41</span>
            <div class="flex gap-1.5">
              <div class="w-4 h-2.5 bg-black rounded-[1px]"></div>
              <div class="w-4 h-2.5 bg-black rounded-[1px]"></div>
            </div>
          </div>

          <!-- App Content -->
          <div class="px-6 pt-4">
            <div class="flex items-center gap-3 mb-8">
              <div class="w-10 h-10 bg-orange-100 rounded-full flex items-center justify-center text-xl">🍕</div>
              <span class="font-semibold text-lg">Your restaurant</span>
            </div>

            <!-- Score Circle -->
            <div class="flex justify-center mb-8">
              <div class="relative w-48 h-48">
                <svg class="w-full h-full transform -rotate-90">
                  <circle cx="96" cy="96" r="88" stroke="#FFE4E1" stroke-width="12" fill="none" />
                  <circle cx="96" cy="96" r="88" stroke="#FF4D4D" stroke-width="12" fill="none" stroke-dasharray="552" stroke-dashoffset="350" stroke-linecap="round" />
                </svg>
                <div class="absolute inset-0 flex flex-col items-center justify-center text-center">
                  <span class="text-5xl font-bold text-gray-900">36</span>
                  <span class="text-sm text-gray-500 font-medium">/ 100</span>
                </div>
              </div>
            </div>

            <div class="text-center mb-8">
              <h3 class="font-medium text-gray-900">Website health</h3>
              <p class="text-red-500 font-medium">Poor</p>
            </div>

            <!-- Stats List -->
            <div class="space-y-4">
              <div class="flex justify-between items-center p-3 bg-red-50 rounded-xl">
                <div class="flex items-center gap-3">
                  <div class="w-2 h-2 rounded-full bg-red-500"></div>
                  <span class="text-sm font-medium">Search results</span>
                </div>
                <span class="text-sm text-gray-500">12/40</span>
              </div>
              <div class="flex justify-between items-center p-3 bg-orange-50 rounded-xl">
                <div class="flex items-center gap-3">
                  <div class="w-2 h-2 rounded-full bg-orange-500"></div>
                  <span class="text-sm font-medium">Guest experience</span>
                </div>
                <span class="text-sm text-gray-500">20/40</span>
              </div>
            </div>
          </div>
          
          <!-- Bottom Nav -->
          <div class="absolute bottom-0 left-0 right-0 bg-white border-t border-gray-100 h-16 flex justify-around items-center px-6">
            <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
            <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
            <div class="w-6 h-6 bg-gray-200 rounded-full"></div>
          </div>
        </div>
      </div>

      <!-- Floating Input Card -->
      <div class="absolute top-[60%] left-1/2 -translate-x-1/2 w-[420px] bg-white rounded-2xl shadow-xl p-4 z-20 border border-gray-100 hidden md:block">
        <div class="flex items-center gap-2 mb-3 text-sm text-gray-500">
          <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
          </svg>
          Scan your site and see what isn't working
        </div>
        <div class="relative">
          <input 
            type="text" 
            placeholder="Find your restaurant name" 
            class="w-full pl-4 pr-32 py-3 bg-gray-50 rounded-xl border-none focus:ring-2 focus:ring-blue-500 outline-none text-sm"
          />
          <button class="absolute right-1.5 top-1.5 bottom-1.5 bg-black text-white text-xs font-medium px-4 rounded-lg hover:bg-gray-800 transition-colors flex items-center gap-1">
            Get my AI report
            <svg class="w-3 h-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</section>
