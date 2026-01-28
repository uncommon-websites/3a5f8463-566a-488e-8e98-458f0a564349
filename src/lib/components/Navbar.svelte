<script lang="ts">
  import NavLink from './NavLink.svelte';
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <!-- Left: Logo & Links -->
      <div class="flex items-center gap-8">
        <a href="/" class="flex items-center gap-2">
          <!-- Logo Placeholder -->
          <div class="w-8 h-8 bg-gradient-to-br from-teal-500 to-cyan-600 rounded-lg flex items-center justify-center text-white font-bold text-xs">
            D
          </div>
        </a>
        <div class="hidden md:flex items-center gap-6">
          <NavLink label="Digital Minds" />
          <NavLink label="Library of Minds" />
        </div>
      </div>

      <!-- Right: Actions -->
      <div class="flex items-center gap-4">
        <NavLink label="Login" />
        <a
          href="#"
          class="bg-gradient-to-r from-teal-500 to-cyan-600 text-white px-4 py-2 rounded-full text-sm font-medium hover:from-teal-600 hover:to-cyan-700 transition-colors"
        >
          Create your clone
        </a>
      </div>
    </div>
  </div>
</nav>
