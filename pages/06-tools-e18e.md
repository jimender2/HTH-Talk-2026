---
transition: slide-left
---

# Tool: e18e — Ecosystem-Level Cleanup

<div class="grid grid-cols-5 gap-6 mt-4">

<div class="col-span-2 space-y-4">
  <div class="text-sm text-gray-300 leading-relaxed">
    <span class="text-blue-400 font-bold">e18e</span> (Ecosystem Performance) is a community initiative replacing bloated, outdated packages with <span class="text-green-400">leaner, modern alternatives</span>.
  </div>

  <div v-click class="space-y-2">
    <div class="bg-gray-800/50 rounded-lg p-3 border border-gray-700">
      <div class="text-sm font-mono">
        <span class="text-red-400 line-through">chalk</span>
        <span class="text-green-400 ml-2">→ picocolors</span>
        <span class="text-gray-500 text-xs ml-2">(88% smaller)</span>
      </div>
    </div>
    <div class="bg-gray-800/50 rounded-lg p-3 border border-gray-700">
      <div class="text-sm font-mono">
        <span class="text-red-400 line-through">glob</span>
        <span class="text-green-400 ml-2">→ tinyglobby</span>
        <span class="text-gray-500 text-xs ml-2">(95% smaller, no deps)</span>
      </div>
    </div>
    <div class="bg-gray-800/50 rounded-lg p-3 border border-gray-700">
      <div class="text-sm font-mono">
        <span class="text-red-400 line-through">node-fetch</span>
        <span class="text-green-400 ml-2">→ built-in fetch</span>
        <span class="text-gray-500 text-xs ml-2">(0 deps, Node.js 18+)</span>
      </div>
    </div>
    <div class="bg-gray-800/50 rounded-lg p-3 border border-gray-700">
      <div class="text-sm font-mono">
        <span class="text-red-400 line-through">rimraf</span>
        <span class="text-green-400 ml-2">→ `rm -rf` / native</span>
        <span class="text-gray-500 text-xs ml-2">(no JS deps needed)</span>
      </div>
    </div>
  </div>
</div>

<div v-click class="col-span-3 bg-gray-800/40 rounded-lg p-5 border border-gray-700 flex flex-col justify-center">
  <h3 class="text-lg font-bold text-blue-400 mb-3">Security Wins from e18e</h3>
  <div class="space-y-3">
    <div class="flex items-start gap-2">
      <span class="text-green-400 mt-0.5">📦</span>
      <span class="text-sm text-gray-300">Fewer dependencies = <span class="text-green-300 font-semibold">smaller attack surface</span></span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-blue-400 mt-0.5">🔄</span>
      <span class="text-sm text-gray-300">Replace unmaintained packages with <span class="text-blue-300 font-semibold">actively maintained</span> alternatives</span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-purple-400 mt-0.5">📋</span>
      <span class="text-sm text-gray-300"><span class="text-purple-300 font-semibold">Public manifest</span> of suggested replacements at <a href="https://e18e.dev" class="underline text-blue-300">e18e.dev</a></span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-orange-400 mt-0.5">🔍</span>
      <span class="text-sm text-gray-300">Integrated with <span class="text-orange-300 font-semibold">npmgraph</span> — see replacement suggestions visually</span>
    </div>
    <div class="flex items-start gap-2">
      <span class="text-teal-400 mt-0.5">🏢</span>
      <span class="text-sm text-gray-300">Adopted by major projects: <span class="text-teal-300 font-semibold">Storybook, Astro, Vite, ESLint</span></span>
    </div>
  </div>
</div>

</div>

<div v-click class="mt-6 p-3 bg-blue-900/20 border border-blue-500/30 rounded-lg text-center text-sm text-blue-300">
  🌐 <a href="https://e18e.dev" class="underline">e18e.dev</a> • <a href="https://github.com/e18e" class="underline">github.com/e18e</a> — Community-driven, OSS
</div>

<!--
e18e is more than a tool — it's a movement.

Started by the community to clean up the JS ecosystem.
They maintain a manifest of suggested package replacements.

The idea: many packages exist because a need wasn't met years ago.
Now the language or runtime has evolved, but the packages remain.

Examples:
- chalk was great when we needed color in terminal, but picocolors is 88% smaller
- glob has many features nobody uses, tinyglobby is minimal
- node-fetch was needed before Node 18 added fetch natively
- rimraf was needed before Node 14 added fs.rmSync

By making these replacements, you eliminate transitive dependencies and reduce risk.
-->
