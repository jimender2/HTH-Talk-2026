---
transition: fade-out
---

# The "Dependency Hell" Crisis

<div class="flex gap-6 mt-4">
  <div class="w-1/2 bg-gray-900 rounded-lg p-4 border border-gray-700 font-mono text-[11px] leading-relaxed">
    <div class="text-gray-500 text-xs mb-1">node_modules/</div>
    <div class="text-blue-400">express/</div>
    <div class="text-gray-500 ml-4">├── accepts/</div>
    <div class="text-gray-500 ml-4">├── body-parser/</div>
    <div class="text-gray-500 ml-4">├── cookie/</div>
    <div class="text-gray-500 ml-4">├── debug/</div>
    <div class="text-gray-500 ml-4">├── etag/</div>
    <div class="text-gray-500 ml-4">├── fresh/</div>
    <div class="text-gray-500 ml-4">├── ...</div>
    <div class="text-red-400 ml-4">lodash/ <span class="text-gray-500 text-[10px]">@3.0.0</span></div>
    <div class="text-blue-400">react/</div>
    <div class="text-gray-500 ml-4">├── loose-envify/</div>
    <div class="text-gray-500 ml-4">├── object-assign/</div>
    <div class="text-gray-500 ml-4">├── prop-types/</div>
    <div class="text-gray-500 ml-4">├── scheduler/</div>
    <div class="text-red-400 ml-4">lodash/ <span class="text-gray-500 text-[10px]">@4.0.0</span></div>
    <div class="text-blue-400">webpack/</div>
    <div class="text-gray-500 ml-4">├── acorn/</div>
    <div class="text-gray-500 ml-4">├── tapable/</div>
    <div class="text-gray-500 ml-4">├── watchpack/</div>
    <div class="text-gray-500 ml-4">├── ...</div>
    <div class="text-gray-500">+847 more packages</div>
  </div>

  <div class="w-1/2 space-y-3 flex flex-col justify-center">
    <div class="flex items-center gap-4">
      <div class="text-5xl font-black text-red-500 tracking-tight shrink-0">1,000+</div>
      <div class="text-xs uppercase tracking-wider text-gray-400 font-semibold leading-tight">
        Average transitive<br>dependencies per project
      </div>
    </div>
    <div v-click class="bg-red-900/20 border-l-4 border-red-500 rounded-r-lg p-3">
      <div class="text-sm font-bold text-red-400">⚡ Uncontrolled Bloat</div>
      <div class="text-xs text-gray-300 mt-1">Attack surfaces scale exponentially. One package pulls in dozens of sub-dependencies — a massive unmanaged shadow ecosystem.</div>
    </div>
    <div v-click class="bg-orange-900/20 border-l-4 border-orange-500 rounded-r-lg p-3">
      <div class="text-sm font-bold text-orange-400">🕵️ Duplicate Versions</div>
      <div class="text-xs text-gray-300 mt-1">Same package, different versions, installed multiple times. Each copy needs its own patch.</div>
    </div>
    <div v-click class="bg-yellow-900/20 border-l-4 border-yellow-500 rounded-r-lg p-3">
      <div class="text-sm font-bold text-yellow-400">🔗 Inherited Risk</div>
      <div class="text-xs text-gray-300 mt-1">You trust thousands of unknown maintainers sitting 5–10 layers deep in your tree.</div>
    </div>
  </div>
</div>