<script lang="ts">
  // FeaturesTabs component
  let activeTab = 0;
  const tabs = [
    "More Google Traffic",
    "More Online Sales",
    "More Repeat Orders",
    "More App Downloads"
  ];
</script>

<section class="py-16 md:py-24">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12 max-w-2xl mx-auto">
      With Owner, you get more traffic, more sales, more repeat customers
    </h2>

    <!-- Tabs -->
    <div class="flex flex-wrap justify-center gap-8 mb-12 border-b border-gray-200">
      {#each tabs as tab, i}
        <button 
          class="pb-4 text-sm font-medium transition-colors relative {activeTab === i ? 'text-gray-900' : 'text-gray-400 hover:text-gray-600'}"
          onclick={() => activeTab = i}
        >
          <span class="mr-2 text-xs opacity-60">{i + 1}.</span>
          {tab}
          {#if activeTab === i}
            <div class="absolute bottom-0 left-0 right-0 h-0.5 bg-gray-900"></div>
          {/if}
        </button>
      {/each}
    </div>

    <!-- Content -->
    <div class="bg-[#EBE8E2] rounded-[32px] p-8 md:p-16 relative overflow-hidden">
      <!-- Background Elements -->
      <div class="absolute top-0 right-0 w-2/3 h-full bg-gradient-to-l from-[#E5E2DC] to-transparent pointer-events-none"></div>

      <div class="grid md:grid-cols-2 gap-12 items-center relative z-10">
        <div class="max-w-md">
          <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6 leading-tight">
            Upgrade your SEO <br />
            <span class="text-gray-500 font-normal">With Owner, your website gets way more Google traffic</span>
          </h3>
        </div>

        <div class="relative">
          <!-- Phone Mockup -->
          <div class="relative mx-auto w-[280px] md:w-[320px] bg-black rounded-[40px] p-3 shadow-2xl border-[6px] border-gray-800 rotate-[-5deg] transform translate-x-8">
            <div class="bg-white rounded-[32px] overflow-hidden h-[500px] relative">
               <!-- Mock Content -->
               <div class="h-full bg-gray-50 p-4">
                 <div class="w-full h-8 bg-gray-200 rounded-lg mb-4"></div>
                 <div class="grid grid-cols-2 gap-3">
                    <div class="h-32 bg-gray-200 rounded-xl"></div>
                    <div class="h-32 bg-gray-200 rounded-xl"></div>
                    <div class="h-32 bg-gray-200 rounded-xl"></div>
                    <div class="h-32 bg-gray-200 rounded-xl"></div>
                 </div>
               </div>
            </div>
          </div>
          
          <!-- Floating Elements -->
          <div class="absolute top-1/4 -left-12 bg-white p-4 rounded-xl shadow-lg max-w-[200px] transform rotate-3">
             <div class="h-2 w-20 bg-gray-200 rounded mb-2"></div>
             <div class="h-2 w-32 bg-gray-200 rounded"></div>
          </div>
        </div>
      </div>

      <!-- Navigation Buttons -->
      <div class="absolute bottom-8 left-8 flex gap-2">
        <button class="w-10 h-10 rounded-full bg-white/50 hover:bg-white flex items-center justify-center transition-colors">
          ←
        </button>
        <button class="w-10 h-10 rounded-full bg-white/50 hover:bg-white flex items-center justify-center transition-colors">
          →
        </button>
      </div>
    </div>
  </div>
</section>
