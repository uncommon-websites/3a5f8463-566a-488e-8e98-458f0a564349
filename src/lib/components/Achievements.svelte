<script lang="ts">
  let activeTab = 'Today';
  const tabs = ['Today', 'Day 3', 'Day 7'];
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-4xl font-bold mb-12">
      What you can achieve with<br />Delphi <span class="bg-teal-100 text-teal-600 px-2 rounded">in just 7 days</span>
    </h2>
    
    <div class="flex justify-center gap-4 mb-16">
      {#each tabs as tab}
        <button 
          class="px-6 py-2 rounded-full text-sm font-medium transition-colors {activeTab === tab ? 'bg-gray-800 text-white' : 'bg-gray-200 text-gray-500 hover:bg-gray-300'}"
          on:click={() => activeTab = tab}
        >
          {tab}
        </button>
      {/each}
    </div>
    
    <div class="grid md:grid-cols-3 gap-8 text-left">
      <!-- Card 1 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Create your clone</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Upload your content (podcasts, videos, articles)</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Train your voice model with audio samples</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Test your Digital Mind with real questions</span>
          </li>
        </ul>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Deploy everywhere</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Connect WhatsApp, SMS, and email</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Share your clone link with your audience</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Start conversations across all platforms</span>
          </li>
        </ul>
      </div>

      <!-- Card 3 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100">
        <h3 class="font-bold text-lg mb-6">Scale infinitely</h3>
        <ul class="space-y-4">
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Handle thousands of conversations simultaneously</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Provide personalized mentorship at scale</span>
          </li>
          <li class="flex items-start gap-3">
            <svg class="w-5 h-5 text-teal-500 shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
            <span class="text-sm text-gray-600">Win back hours per day for deep work</span>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="mt-16">
       <button class="bg-gradient-to-r from-teal-500 to-cyan-600 text-white px-8 py-3 rounded-full text-lg font-medium hover:from-teal-600 hover:to-cyan-700 transition-colors">
        Create your clone
      </button>
    </div>
  </div>
</section>
