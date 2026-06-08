<script>
  // Hero component
</script>

<section class="px-6 pt-12 pb-6">
  <div class="grid grid-cols-1 md:grid-cols-12 gap-8 mb-12">
    <div class="md:col-span-7">
      <h1 class="text-5xl md:text-[64px] leading-[1.1] tracking-tight text-gray-900 font-normal max-w-3xl">
        Conversion-optimized landing pages for ambitious startups
      </h1>
    </div>
    <div class="md:col-span-5 flex flex-col justify-between">
      <p class="text-gray-500 text-sm max-w-xs md:ml-auto leading-relaxed">
        Launch world-class landing pages in hours, not weeks, using AI-powered design and rapid iteration—built for SF’s fastest-moving founders.
      </p>
    </div>
  </div>

  <div class="flex flex-col md:flex-row items-start md:items-center justify-between mb-6 gap-4">
    <div class="flex items-center gap-4">
      <a href="/" class="bg-black text-white px-6 py-3 text-sm hover:bg-gray-800 transition-colors">See demo sites</a>
      <span class="text-[10px] text-gray-500 max-w-[100px] leading-tight">Tailored for pre-seed founders</span>
    </div>
    <div class="text-[10px] text-gray-400 font-mono tracking-widest">
      LIVE WITH YC F25
    </div>
  </div>

  <!-- Hero Image -->
  <div class="relative w-full h-[500px] overflow-hidden bg-emerald-800">
    <!-- Placeholder for the blurry image -->
    <div class="absolute inset-0 bg-gradient-to-tr from-emerald-900 via-emerald-600 to-emerald-400 opacity-80 mix-blend-multiply"></div>
    
    <!-- Abstract blurred shapes to mimic the person running -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-emerald-300 rounded-full blur-[100px] opacity-40"></div>
    <div class="absolute top-1/4 left-1/3 w-[300px] h-[300px] bg-white rounded-full blur-[80px] opacity-20"></div>

    <!-- Overlay Lines -->
    <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-40" viewBox="0 0 1000 500" preserveAspectRatio="none">
       <path d="M0,500 Q200,100 500,250 T1000,0" fill="none" stroke="white" stroke-width="1" />
       <path d="M-100,600 Q300,0 600,300 T1200,-100" fill="none" stroke="white" stroke-width="1" opacity="0.5" />
    </svg>

    <!-- Center Text -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 flex items-center gap-2">
      <div class="w-0.5 h-3 bg-white"></div>
      <span class="text-white text-[10px] tracking-[0.2em] font-medium">LAUNCH FASTER</span>
    </div>
  </div>
</section>
