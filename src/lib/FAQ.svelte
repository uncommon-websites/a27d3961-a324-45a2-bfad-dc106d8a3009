<script lang="ts">
  // FAQ component
  let openIndex: number | null = null;

  const faqs = [
    "Do I have to trust AI with my company's brand?",
    "How does Semiotic help create landing pages?",
    "I want to showcase multiple products. Can you support this?",
    "I'm a founder. How do I start with Semiotic?",
    "Is Semiotic available for all startups?",
    "Why do founders choose Semiotic for landing pages?",
    "What are the benefits of sharing my site needs with Semiotic?"
  ];

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="px-6 py-24 bg-gray-50">
  <div class="grid grid-cols-1 md:grid-cols-12 gap-8">
    <div class="md:col-span-4">
      <h2 class="text-3xl md:text-4xl font-normal text-gray-900 mb-6 max-w-xs leading-tight">
        Your questions about Semiotic, answered
      </h2>
      <a href="/" class="text-sm text-gray-500 underline underline-offset-4 hover:text-black">Visit support center</a>
    </div>
    <div class="md:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as question, i}
          <div class="border-b border-gray-200">
            <button 
              class="w-full py-6 flex items-center justify-between text-left hover:bg-gray-100/50 transition-colors group"
              onclick={() => toggle(i)}
            >
              <span class="text-sm text-gray-700 group-hover:text-black">{question}</span>
              <span class="text-gray-400 font-light text-xl ml-4">
                {openIndex === i ? '−' : '+'}
              </span>
            </button>
            {#if openIndex === i}
              <div class="pb-6 text-sm text-gray-500 leading-relaxed">
                <!-- Placeholder answer -->
                Have more questions? Our team is happy to talk — Semiotic lets you launch best-in-class landing pages powered by AI-driven design, tailored for early-stage founders.
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
