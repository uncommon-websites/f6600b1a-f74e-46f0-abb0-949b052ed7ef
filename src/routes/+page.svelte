<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Button from '$lib/components/Button.svelte';
  import Apple from '$lib/components/icons/Apple.svelte';
  import MapPinIcon from '$lib/components/icons/MapPinIcon.svelte';
  import CalendarIcon from '$lib/components/icons/CalendarIcon.svelte';
  import ToddlerIcon from '$lib/components/icons/ToddlerIcon.svelte';
  import Laurel from '$lib/components/icons/Laurel.svelte';
  import PhoneUI from '$lib/components/PhoneUI.svelte';
  import ToddleLogo from '$lib/components/icons/ToddleLogo.svelte';
</script>

<div class="min-h-screen bg-white text-black font-sans selection:bg-gray-200">
  <Header />

  <main class="flex flex-col items-center w-full">
    <!-- Hero Section -->
    <section class="flex flex-col items-center text-center pt-10 pb-12 px-4 max-w-4xl mx-auto">
      <h2 class="text-sm font-semibold mb-6">Toddle</h2>
      
      <h1 class="text-5xl md:text-7xl font-bold tracking-tight leading-[1.1] mb-10">
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>Find</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-blue-50 rounded-2xl align-middle mx-1">
            <CalendarIcon className="w-6 h-6 md:w-8 md:h-8 text-blue-600" />
          </span>
          <span>weekend</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>activities for</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-blue-50 rounded-2xl align-middle mx-1">
            <ToddlerIcon className="w-6 h-6 md:w-8 md:h-8 text-blue-600" />
          </span>
          <span>toddlers</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-blue-50 rounded-2xl align-middle mx-1">
            <MapPinIcon className="w-6 h-6 md:w-8 md:h-8 text-blue-600" />
          </span>
          <span>near you</span>
        </div>
      </h1>

      <div class="mb-12">
        <Button>
          <Apple className="w-5 h-5" />
          <span class="text-base">Download for iOS</span>
        </Button>
      </div>

      <!-- Awards/Featured -->
      <div class="flex flex-wrap justify-center gap-8 md:gap-16 text-gray-400 text-[10px] md:text-xs font-medium uppercase tracking-widest">
        <div class="flex items-center gap-2">
          <Laurel className="w-6 h-12 md:w-8 md:h-16 scale-x-[-1]" />
          <div class="flex flex-col items-center leading-tight">
            <span class="text-[8px] md:text-[10px] text-gray-300 mb-0.5">Trusted by</span>
            <span class="font-bold text-gray-300">50K+ Parents</span>
          </div>
          <Laurel className="w-6 h-12 md:w-8 md:h-16" />
        </div>
        <div class="flex items-center gap-2">
          <Laurel className="w-6 h-12 md:w-8 md:h-16 scale-x-[-1]" />
          <div class="flex flex-col items-center leading-tight">
            <span class="text-[8px] md:text-[10px] text-gray-300 mb-0.5">Curating</span>
            <span class="font-bold text-gray-300">Local Activities</span>
          </div>
          <Laurel className="w-6 h-12 md:w-8 md:h-16" />
        </div>
      </div>
    </section>

    <!-- Phone Showcase -->
    <section class="w-full max-w-[1000px] px-4 mb-24 relative flex justify-center">
      <!-- Background glow/shadow simulation -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-gray-100/50 rounded-full blur-3xl -z-10"></div>
      
      <!-- Phone Container -->
      <!-- Since we don't have the hand image, we'll present the phone UI in a nice frame -->
      <div class="relative w-[300px] md:w-[340px] h-[680px] md:h-[720px] transition-transform hover:scale-[1.02] duration-500">
        <PhoneUI />
      </div>
    </section>

    <!-- Features Text -->
    <section class="max-w-4xl mx-auto px-6 pb-32 space-y-24 text-center">
      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Toddle delivers curated weekend activities for toddlers through location-based filtering and age-appropriate recommendations
        </h3>
      </div>

      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Every activity is filtered for practical logistics — nap schedules, diaper changes, parking, and facilities that matter to parents
        </h3>
      </div>

      <div class="space-y-10">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Transform "What do we do this weekend?" from a source of stress into an opportunity for joy with your little one
        </h3>
        
        <div class="pt-4">
          <Button>
            <Apple className="w-5 h-5" />
            <span class="text-base">Download for iOS</span>
          </Button>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="w-full py-12 flex flex-col items-center gap-6 text-center border-t border-gray-100 mt-auto">
      <div class="flex flex-col items-center gap-3">
        <ToddleLogo className="w-8 h-10 text-blue-600" />
        <div class="font-bold text-xl tracking-tight text-gray-800">Toddle</div>
      </div>
      <div class="flex flex-wrap justify-center gap-4 text-xs text-gray-400 font-medium">
        <a href="#" class="hover:text-blue-600 transition-colors">App Store</a>
        <span>•</span>
        <a href="#" class="hover:text-blue-600 transition-colors">Contact</a>
        <span>•</span>
        <a href="#" class="hover:text-blue-600 transition-colors">X (FKA Twitter)</a>
        <span>•</span>
        <a href="#" class="hover:text-blue-600 transition-colors">Privacy policy</a>
      </div>
      <div class="text-[10px] text-gray-300">
        Crafted in Amsterdam and Lisbon
      </div>
    </footer>
  </main>
</div>


