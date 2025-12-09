<script lang="ts">
  // FooterCTA component
</script>

<section class="py-4 px-4 md:px-8">
  <div class="max-w-[1400px] mx-auto bg-[#B0A695] rounded-[32px] overflow-hidden relative min-h-[400px] flex items-center">
    <!-- Background Image/Texture -->
    <img 
      src="https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&q=80&w=1600" 
      alt="Background" 
      class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-overlay"
    />
    
    <div class="relative z-10 w-full px-8 md:px-16 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <h2 class="text-3xl md:text-5xl font-bold text-white mb-8 leading-tight">
          The easiest way to grow your restaurant online.
        </h2>
        <button class="bg-black text-white px-6 py-3 rounded-lg font-medium hover:bg-gray-900 transition-colors inline-flex items-center gap-2">
          Get a free demo
          <span>›</span>
        </button>
      </div>

      <div class="relative h-[400px] hidden md:block">
        <!-- Phone Mockup -->
        <div class="absolute right-0 top-1/2 -translate-y-1/2 w-[300px] rotate-[-10deg] transform translate-y-12">
            <div class="bg-black rounded-[40px] p-2 border-[4px] border-gray-800 shadow-2xl">
              <div class="bg-white h-[500px] rounded-[32px] overflow-hidden relative">
                <img 
                  src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?auto=format&fit=crop&q=80&w=600" 
                  alt="Food App" 
                  class="w-full h-full object-cover"
                />
                <!-- Floating Card -->
                <div class="absolute bottom-8 left-4 right-4 bg-white p-4 rounded-xl shadow-lg">
                  <div class="text-xs font-bold text-gray-900 mb-1">Hearty Zucchini</div>
                  <p class="text-[10px] text-gray-500 mb-2">A hearty bowl of slow cooked yellow squash with a rich savory taste...</p>
                  <div class="flex justify-between items-center">
                    <span class="text-xs font-bold">$14.50</span>
                    <div class="w-6 h-6 bg-gray-100 rounded-full flex items-center justify-center text-xs">+</div>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
