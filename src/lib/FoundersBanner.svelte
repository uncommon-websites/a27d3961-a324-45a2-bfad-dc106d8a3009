<script>
  // Founders Banner component
</script>

<section class="px-6 py-12">
  <div class="relative w-full rounded-[32px] overflow-hidden bg-[#0a2533] min-h-[400px] flex flex-col items-center justify-center text-center px-4 py-20">
    <!-- Background effects -->
    <div class="absolute inset-0 bg-gradient-to-b from-[#0e3b4e] to-[#05151d] opacity-80"></div>
    
    <!-- Abstract blurred shapes -->
    <div class="absolute top-0 right-0 w-[400px] h-[400px] bg-blue-500 rounded-full blur-[120px] opacity-20"></div>
    <div class="absolute bottom-0 left-0 w-[400px] h-[400px] bg-teal-500 rounded-full blur-[120px] opacity-10"></div>

    <!-- Curved Lines Overlay -->
    <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-30" viewBox="0 0 1000 400" preserveAspectRatio="none">
       <path d="M-100,400 Q200,50 500,200 T1100,0" fill="none" stroke="white" stroke-width="1" />
       <path d="M0,300 Q400,100 700,300 T1200,100" fill="none" stroke="white" stroke-width="1" opacity="0.5" />
    </svg>

    <!-- Content -->
    <div class="relative z-10 max-w-2xl mx-auto">
      <div class="absolute top-8 left-8 md:top-12 md:left-12 flex items-center gap-2">
         <div class="w-0.5 h-3 bg-white/50"></div>
         <span class="text-white/70 text-[10px] tracking-widest font-medium uppercase">For Founders</span>
      </div>

      <h2 class="text-3xl md:text-4xl font-normal text-white mb-6 leading-tight">
        AI-crafted landing pages for tomorrow’s top startups
      </h2>
      <p class="text-gray-300 text-sm mb-10 max-w-lg mx-auto leading-relaxed">
        Semiotic accelerates your go-to-market with conversion-driven landing pages—designed, built, and iterated by AI in a matter of hours, not weeks. Founders can focus on building product while we deliver compelling design.
      </p>
      
      <a href="/" class="inline-block border border-white/20 text-white px-6 py-3 text-sm hover:bg-white/10 transition-colors rounded-sm">
        Explore Semiotic for startups
      </a>
    </div>
  </div>
</section>
