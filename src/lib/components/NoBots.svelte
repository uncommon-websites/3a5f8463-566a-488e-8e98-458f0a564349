<script lang="ts">
  // Authentic Voice Section
</script>

<section class="py-24 bg-gray-50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-2 gap-16 items-center">
      <div>
        <h2 class="text-3xl font-bold mb-6">Your authentic voice, perfectly replicated</h2>
        <p class="text-gray-600 mb-8">
          Delphi doesn't just mimic words—it captures your essence. Through advanced voice training and content analysis, your Digital Mind sounds genuinely like you:
        </p>
        
        <ul class="space-y-4">
          {#each ['Maintains your unique tone and speaking style', 'Reflects your values and philosophical approach', 'Adapts responses based on your actual expertise', 'Never improvises without your consent'] as item}
            <li class="flex items-start gap-3">
              <div class="w-5 h-5 rounded-full bg-teal-100 flex items-center justify-center mt-0.5 shrink-0">
                <svg class="w-3 h-3 text-teal-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
                </svg>
              </div>
              <span class="text-gray-700 text-sm">{item}</span>
            </li>
          {/each}
        </ul>
      </div>
      
      <div class="relative">
        <!-- Voice Training Mockup -->
        <div class="bg-gradient-to-br from-teal-100 to-cyan-100 rounded-2xl p-8 shadow-lg">
           <div class="bg-white rounded-xl overflow-hidden shadow-2xl relative aspect-video flex items-center justify-center p-8">
              <!-- Voice Waveform Visualization -->
              <div class="absolute inset-0 flex items-center justify-center">
                <div class="flex items-end gap-1 h-32">
                  {#each Array(40) as _, i}
                    <div class="w-1 bg-gradient-to-t from-teal-500 to-cyan-500 rounded-full" style="height: {20 + Math.sin(i * 0.5) * 50}%"></div>
                  {/each}
                </div>
              </div>
              
              <!-- Voice Training Badge -->
              <div class="absolute top-4 left-1/2 -translate-x-1/2 bg-white rounded-full px-6 py-3 flex items-center gap-3 shadow-xl border border-gray-100 z-10">
                 <div class="w-3 h-3 rounded-full bg-teal-500 animate-pulse"></div>
                 <span class="text-gray-900 text-sm font-medium">Voice Training: 98% Accuracy</span>
              </div>

              <!-- Stats -->
              <div class="absolute bottom-4 left-4 right-4 flex justify-between">
                <div class="bg-white/90 backdrop-blur-sm rounded-lg px-4 py-2 shadow-md">
                  <div class="text-xs text-gray-500">Hours Processed</div>
                  <div class="text-lg font-bold text-gray-900">50+</div>
                </div>
                <div class="bg-white/90 backdrop-blur-sm rounded-lg px-4 py-2 shadow-md">
                  <div class="text-xs text-gray-500">Voice Match</div>
                  <div class="text-lg font-bold text-teal-600">98%</div>
                </div>
                <div class="bg-white/90 backdrop-blur-sm rounded-lg px-4 py-2 shadow-md">
                  <div class="text-xs text-gray-500">Content Items</div>
                  <div class="text-lg font-bold text-gray-900">10k+</div>
                </div>
              </div>
           </div>
        </div>
        <p class="text-xs text-gray-500 mt-4 text-center">
          Advanced AI analyzes your content to capture your unique voice patterns and expertise.
        </p>
      </div>
    </div>
    
    <div class="mt-16 p-6 bg-teal-50 rounded-xl border border-teal-100">
      <p class="text-sm text-teal-800">
        <span class="font-bold">The voice replication is eerily accurate</span>—it captures not just how I sound, but how I think and communicate. My audience can't tell the difference between my clone and me having a real conversation with them.
      </p>
      <div class="mt-2 text-xs text-teal-600 font-medium">Vanessa Van Edwards • Behavioral Scientist</div>
    </div>
  </div>
</section>
