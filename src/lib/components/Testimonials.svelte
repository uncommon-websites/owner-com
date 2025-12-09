<script lang="ts">
  // Testimonials component
  const reviews = [
    {
      text: "The branded website and Online ordering platform is perfect for our guest and growing my business.",
      author: "Steven T.",
      avatar: "ST"
    },
    {
      text: "With Owner.com I keep all money from sales and only pay minimal fee on delivery cost.",
      author: "Mohammed A.",
      avatar: "MA"
    },
    {
      text: "Owner.com has almost everything you need to run your restaurant online. An awesome partner to have for restaurants.",
      author: "John A.",
      avatar: "JA"
    },
    {
      text: "Owner.com has been an absolute lifesaver when it comes to minimizing third-party service fees and driving direct store sales.",
      author: "Tara B.",
      avatar: "TB"
    },
    {
      text: "My restaurants operate very late, yet Owner Customer's Support has ALWAYS been active and able to help me with any concerns!",
      author: "Gary S.",
      avatar: "GS"
    },
    {
      text: "They are helping us take back more control of our business and compete with larger companies because the technology is great!",
      author: "Michael B.",
      avatar: "MB"
    }
  ];
</script>

<section class="py-16 md:py-24 bg-[#F4F2ED]">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">See why we're rated #1 <br /> in restaurant tech</h2>
    
    <div class="flex justify-center gap-4 mb-12">
      <div class="bg-white px-4 py-2 rounded border border-gray-200 text-xs font-bold text-gray-600 uppercase tracking-wider">
        Capterra Shortlist
      </div>
      <div class="bg-white px-4 py-2 rounded border border-gray-200 text-xs font-bold text-gray-600 uppercase tracking-wider">
        Software Advice FrontRunners
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 text-left mb-12">
      {#each reviews as review}
        <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
          <div class="flex text-yellow-400 mb-3 text-sm">★★★★★</div>
          <p class="text-gray-600 text-sm mb-6 leading-relaxed min-h-[80px]">{review.text}</p>
          <div class="flex items-center gap-3">
            <div class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-xs font-bold text-gray-600">
              {review.avatar}
            </div>
            <span class="text-sm font-medium text-gray-900">{review.author}</span>
          </div>
        </div>
      {/each}
    </div>

    <button class="bg-black text-white px-6 py-3 rounded-lg font-medium hover:bg-gray-800 transition-colors inline-flex items-center gap-2">
      See more reviews
      <span class="text-lg">›</span>
    </button>
  </div>
</section>
