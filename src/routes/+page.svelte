<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import TrustedBy from "$lib/components/TrustedBy.svelte";
  import FeaturesTabs from "$lib/components/FeaturesTabs.svelte";
  import Testimonials from "$lib/components/Testimonials.svelte";
  import TechFeatures from "$lib/components/TechFeatures.svelte";
  import SuccessStory1 from "$lib/components/SuccessStory1.svelte";
  import SuccessStory2 from "$lib/components/SuccessStory2.svelte";
  import Beliefs from "$lib/components/Beliefs.svelte";
  import Guides from "$lib/components/Guides.svelte";
  import FooterCTA from "$lib/components/FooterCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-[#FBFBF9] font-sans text-gray-900 selection:bg-blue-100 selection:text-blue-900">
  <Header />
  
  <main>
    <Hero />
    <TrustedBy />
    <FeaturesTabs />
    <Testimonials />
    <TechFeatures />
    <SuccessStory1 />
    <SuccessStory2 />
    <Beliefs />
    <Guides />
    <FooterCTA />
  </main>

  <Footer />
</div>

