<script lang="ts">
  // TrustedBy component
  const cards = [
    {
      image: "https://images.unsplash.com/photo-1556910103-1c02745a30bf?auto=format&fit=crop&q=80&w=600",
      text: "Pizza increased direct orders by $10,000/m by Owner.com",
      overlay: "bg-gradient-to-t from-black/80 via-black/20 to-transparent"
    },
    {
      image: "https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&q=80&w=600",
      text: "+$7,000,000/year in direct online sales",
      overlay: "bg-gradient-to-t from-black/80 via-black/20 to-transparent"
    },
    {
      image: "https://images.unsplash.com/photo-1542181961-9590d0c79dab?auto=format&fit=crop&q=80&w=600",
      text: "How Sushi Addicts grew online orders to $210,000 per year with Owner",
      overlay: "bg-gradient-to-t from-black/80 via-black/20 to-transparent"
    },
    {
      image: "https://images.unsplash.com/photo-1551218808-94e220e084d2?auto=format&fit=crop&q=80&w=600",
      text: "+$300,000 Online sales",
      overlay: "bg-gradient-to-t from-black/80 via-black/20 to-transparent"
    }
  ];
</script>

<section class="py-16 md:py-24">
  <div class="max-w-[1400px] mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-2xl md:text-3xl font-bold text-gray-900 mb-8">Trusted by thousands of owners</h2>
    
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
      {#each cards as card}
        <div class="group relative h-[400px] rounded-2xl overflow-hidden cursor-pointer">
          <img 
            src={card.image} 
            alt="Restaurant owner" 
            class="absolute inset-0 w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
          />
          <div class="absolute inset-0 {card.overlay}"></div>
          <div class="absolute bottom-0 left-0 right-0 p-6">
            <p class="text-white font-medium text-lg leading-snug">{card.text}</p>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
