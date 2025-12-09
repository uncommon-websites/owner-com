<script lang="ts">
  // SuccessStory2 component
</script>

<section class="py-16 md:py-24">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8">
    <div class="bg-black text-white rounded-[32px] overflow-hidden">
      <div class="grid md:grid-cols-12">
        <!-- Image Side -->
        <div class="md:col-span-5 relative h-[400px] md:h-auto group cursor-pointer">
          <img 
            src="https://images.unsplash.com/photo-1583394293214-28ded15ee548?auto=format&fit=crop&q=80&w=800" 
            alt="Yuliana Vasquez" 
            class="absolute inset-0 w-full h-full object-cover opacity-80 transition-opacity group-hover:opacity-100"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent md:bg-gradient-to-r md:from-transparent md:to-black/80"></div>
          
          <div class="absolute bottom-8 left-8">
            <p class="font-bold text-lg">Yuliana Vasquez</p>
            <p class="text-sm text-gray-300">Owner at Samos Oaxaca</p>
          </div>

          <div class="absolute bottom-8 right-8 w-10 h-10 bg-white/20 backdrop-blur-md rounded-full flex items-center justify-center pl-1 hover:bg-white/30 transition-colors">
            <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24">
              <path d="M8 5v14l11-7z" />
            </svg>
          </div>
        </div>

        <!-- Content Side -->
        <div class="md:col-span-7 p-8 md:p-16 flex flex-col justify-center bg-white">
          <blockquote class="text-2xl md:text-3xl font-medium text-gray-900 mb-12 leading-tight">
            "Owner.com is the secret to our online success. It makes online marketing so easy, and our guests love using our new ordering system and app."
          </blockquote>

          <div class="grid grid-cols-2 gap-8 mb-12">
            <div>
              <div class="text-3xl font-bold text-gray-900 mb-1">+$150,000</div>
              <div class="text-sm text-gray-500">Online sales</div>
            </div>
            <div>
              <div class="text-3xl font-bold text-gray-900 mb-1">+377%</div>
              <div class="text-sm text-gray-500">Growth</div>
            </div>
          </div>

          <div>
            <button class="bg-gray-100 hover:bg-gray-200 text-gray-900 px-6 py-3 rounded-lg font-medium transition-colors inline-flex items-center gap-2">
              See Yuliana's story
              <span>›</span>
            </button>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Dots -->
    <div class="flex justify-center gap-2 mt-8">
      <div class="w-8 h-1 bg-blue-600 rounded-full"></div>
      <div class="w-2 h-1 bg-gray-300 rounded-full"></div>
      <div class="w-2 h-1 bg-gray-300 rounded-full"></div>
      <div class="w-2 h-1 bg-gray-300 rounded-full"></div>
    </div>
  </div>
</section>
