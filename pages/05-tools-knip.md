---
transition: slide-left
---

# Tool: knip — Find Dead Code

<div class="grid grid-cols-2 gap-6 mt-4">
  <div class="space-y-4">
    <div class="text-sm text-gray-300">
      <span class="text-green-400 font-bold">knip</span> finds files, exports, and dependencies that are <span class="text-red-400">never used</span>.
    </div>
    <div v-click class="bg-gray-900 rounded-lg p-4 border border-gray-700 font-mono text-xs leading-relaxed">
      <div class="text-green-400">$ npx knip</div>
      <div class="text-gray-500 mt-2">Unused files (3)</div>
      <div class="text-red-400 ml-4">src/legacy/utils.ts</div>
      <div class="text-red-400 ml-4">src/old-migration.ts</div>
      <div class="text-red-400 ml-4">src/experimental/feature.ts</div>
      <div class="text-gray-500 mt-2">Unused dependencies (5)</div>
      <div class="text-red-400 ml-4">lodash  (used by legacy code)</div>
      <div class="text-red-400 ml-4">moment  (replaced by date-fns)</div>
      <div class="text-red-400 ml-4">chalk   (unused import)</div>
    </div>
    <div v-click class="text-sm text-gray-400 leading-relaxed">
      ✅ Detect unused dependencies in package.json<br>
      ✅ Find orphaned files and dead exports<br>
      ✅ CI-ready — exits non-zero on findings
    </div>
  </div>
  <div v-click class="bg-gray-800/50 rounded-xl p-6 border border-orange-500/30 flex flex-col justify-center">
    <h3 class="text-lg font-bold text-orange-400 mb-4">Why Security Teams Love It</h3>
    <div class="space-y-4">
      <div class="flex items-start gap-3">
        <span class="text-red-400 text-lg shrink-0">⚠</span>
        <span class="text-sm text-gray-300">Unused code doesn't get security patches — it's a <span class="text-red-300 font-semibold">ticking time bomb</span></span>
      </div>
      <div class="flex items-start gap-3">
        <span class="text-orange-400 text-lg shrink-0">📐</span>
        <span class="text-sm text-gray-300">Every unused dependency is <span class="text-orange-300 font-semibold">unnecessary attack surface</span> you're accepting</span>
      </div>
      <div class="flex items-start gap-3">
        <span class="text-green-400 text-lg shrink-0">📉</span>
        <span class="text-sm text-gray-300">Track dep count over time — make it a <span class="text-green-300 font-semibold">security KPI</span></span>
      </div>
      <div class="flex items-start gap-3">
        <span class="text-blue-400 text-lg shrink-0">🤖</span>
        <span class="text-sm text-gray-300">Zero-friction: add <code class="text-green-300">npx knip</code> to CI</span>
      </div>
    </div>
  </div>
</div>
<div v-click class="mt-4 p-3 bg-blue-900/20 border border-blue-500/30 rounded-lg text-center text-sm text-blue-300">
  🔗 <a href="https://knip.dev" class="underline">knip.dev</a> — Lars Kappert (@webpro), OSS
</div>

<!--
knip is probably the single highest-impact tool you can introduce as a security person.

How it works:
- Statically analyzes your codebase
- Tracks imports, exports, and references
- Cross-references against your package.json
- Reports unused files, exports, and dependencies

Why it matters for security:
- Unused code is unmaintained code
- Unmaintained code accumulates CVEs
- You're taking on risk for code you don't even use
- It's a cheap win with high ROI

The best part: add it to CI and it becomes a policy enforcement tool.
-->
