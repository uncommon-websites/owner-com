<script lang="ts">
  // Guides component
  const guides = [
    {
      title: "5 Best Restaurant Marketing Ideas For 2024 (with AI Strategies)",
      image: "https://images.unsplash.com/photo-1542038784424-48ed3893c21c?auto=format&fit=crop&q=80&w=600",
      hasPlay: true
    },
    {
      title: "Restaurant SEO Is Easier Than You Think (3 Big Wins)",
      image: "https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&q=80&w=600",
      hasPlay: false
    },
    {
      title: "Buyer's Guide: The Best Restaurant Website Builders",
      image: "https://images.unsplash.com/photo-1556742046-148c6d151377?auto=format&fit=crop&q=80&w=600",
      hasPlay: false
    }
  ];
</script>

<section class="py-16 md:py-24">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-end mb-12">
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900 max-w-lg">
        See our free guides on growing your restaurant
      </h2>
      <button class="bg-black text-white px-6 py-3 rounded-lg font-medium hover:bg-gray-800 transition-colors hidden md:block">
        Read the blog ›
      </button>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      {#each guides as guide}
        <div class="group relative h-[300px] rounded-2xl overflow-hidden cursor-pointer">
          <img 
            src={guide.image} 
            alt={guide.title} 
            class="absolute inset-0 w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/20 to-transparent"></div>
          
          <div class="absolute bottom-0 left-0 right-0 p-6">
            <h3 class="text-white font-bold text-lg leading-snug">{guide.title}</h3>
          </div>

          {#if guide.hasPlay}
            <div class="absolute bottom-6 right-6 w-8 h-8 bg-white rounded-full flex items-center justify-center pl-0.5">
              <svg class="w-3 h-3 text-black" fill="currentColor" viewBox="0 0 24 24">
                <path d="M8 5v14l11-7z" />
              </svg>
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</section>
