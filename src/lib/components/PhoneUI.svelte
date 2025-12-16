<div class="relative bg-black rounded-[3rem] p-3 w-full h-full shadow-2xl ring-1 ring-gray-900/5">
  <!-- Power Button -->
  <div class="absolute -right-[2px] top-24 w-[2px] h-12 bg-gray-800 rounded-r-md"></div>
  <!-- Volume Buttons -->
  <div class="absolute -left-[2px] top-24 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>
  <div class="absolute -left-[2px] top-36 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>

  <!-- Screen -->
  <div class="bg-white w-full h-full rounded-[2.5rem] overflow-hidden relative flex flex-col">
    <!-- Status Bar / Notch Area -->
    <div class="h-12 w-full flex justify-center items-start pt-2 absolute top-0 left-0 z-20">
      <div class="w-28 h-7 bg-black rounded-full flex items-center justify-center gap-2 px-3">
        <!-- Dynamic Island Content Simulation -->
        <div class="w-full h-full flex items-center justify-between opacity-0">
           <!-- Hidden content just to keep size -->
        </div>
      </div>
    </div>

    <!-- App Content -->
    <div class="flex-1 overflow-y-auto pt-12 px-5 pb-6 text-xs font-medium select-none scrollbar-hide">
      <!-- Header -->
      <div class="mb-5 mt-2">
        <h2 class="text-2xl font-bold tracking-tight mb-1">This Weekend</h2>
        <div class="flex items-center gap-2 text-[11px] text-gray-500">
          <span>📍 Brooklyn, NY</span>
          <span>•</span>
          <span>Ages 0-3</span>
        </div>
      </div>

      <!-- Filter Pills -->
      <div class="flex gap-2 mb-5 text-[10px] font-semibold overflow-x-auto scrollbar-hide pb-1">
        <div class="px-3 py-1.5 bg-black text-white rounded-full whitespace-nowrap">All Activities</div>
        <div class="px-3 py-1.5 bg-gray-100 text-gray-600 rounded-full whitespace-nowrap">Indoor</div>
        <div class="px-3 py-1.5 bg-gray-100 text-gray-600 rounded-full whitespace-nowrap">Outdoor</div>
        <div class="px-3 py-1.5 bg-gray-100 text-gray-600 rounded-full whitespace-nowrap">Free</div>
      </div>

      <!-- Activity Cards -->
      <div class="space-y-4">
        <!-- Activity 1 -->
        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex justify-between items-start">
            <div class="flex-1">
              <h3 class="font-bold text-sm mb-1">Story Time at Library</h3>
              <p class="text-[11px] text-gray-500 leading-relaxed">Interactive reading session for toddlers with songs and movement</p>
            </div>
            <div class="text-lg ml-2">📚</div>
          </div>
          <div class="flex items-center gap-3 text-[10px] text-gray-600 font-medium">
            <span>📍 0.8 mi</span>
            <span>•</span>
            <span>⏱️ 30 min</span>
            <span>•</span>
            <span class="text-green-600 font-semibold">Free</span>
          </div>
        </div>

        <!-- Activity 2 -->
        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex justify-between items-start">
            <div class="flex-1">
              <h3 class="font-bold text-sm mb-1">Prospect Park Playground</h3>
              <p class="text-[11px] text-gray-500 leading-relaxed">Toddler-safe play area with swings, sandbox, and shade</p>
            </div>
            <div class="text-lg ml-2">🌳</div>
          </div>
          <div class="flex items-center gap-3 text-[10px] text-gray-600 font-medium">
            <span>📍 1.2 mi</span>
            <span>•</span>
            <span>⏱️ 1-2 hrs</span>
            <span>•</span>
            <span class="text-green-600 font-semibold">Free</span>
          </div>
        </div>

        <!-- Activity 3 -->
        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex justify-between items-start">
            <div class="flex-1">
              <h3 class="font-bold text-sm mb-1">Music Together Class</h3>
              <p class="text-[11px] text-gray-500 leading-relaxed">Parent-child music class with instruments and movement</p>
            </div>
            <div class="text-lg ml-2">🎵</div>
          </div>
          <div class="flex items-center gap-3 text-[10px] text-gray-600 font-medium">
            <span>📍 0.5 mi</span>
            <span>•</span>
            <span>⏱️ 45 min</span>
            <span>•</span>
            <span>$15</span>
          </div>
        </div>

        <!-- Activity 4 -->
        <div class="bg-gray-50 rounded-2xl p-4 space-y-2">
          <div class="flex justify-between items-start">
            <div class="flex-1">
              <h3 class="font-bold text-sm mb-1">Children's Museum</h3>
              <p class="text-[11px] text-gray-500 leading-relaxed">Sensory play areas designed for crawlers and walkers</p>
            </div>
            <div class="text-lg ml-2">🎨</div>
          </div>
          <div class="flex items-center gap-3 text-[10px] text-gray-600 font-medium">
            <span>📍 2.1 mi</span>
            <span>•</span>
            <span>⏱️ 2-3 hrs</span>
            <span>•</span>
            <span>$12</span>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Home Indicator -->
    <div class="absolute bottom-1 left-1/2 -translate-x-1/2 w-32 h-1 bg-black rounded-full opacity-20"></div>
  </div>
</div>

