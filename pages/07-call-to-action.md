---
layout: center
transition: slide-left
class: text-center
---

# How Security Teams Drive This

<div class="grid grid-cols-3 gap-4 mt-6 max-w-4xl mx-auto">

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">🔍</div>
  <div class="font-bold text-blue-400 text-sm mb-1">Audit & Measure</div>
  <div class="text-xs text-gray-400">Count total deps with <code class="text-blue-300">npm ls --all</code>. Track over time. Make it visible.</div>
</div>

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">🧹</div>
  <div class="font-bold text-green-400 text-sm mb-1">Automate with knip</div>
  <div class="text-xs text-gray-400">Add to CI. Block PRs that add unused deps. <span class="text-green-300">Policy > nagging</span>.</div>
</div>

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">🌐</div>
  <div class="font-bold text-purple-400 text-sm mb-1">Push e18e replacements</div>
  <div class="text-xs text-gray-400">Show devs the manifest. Let them swap bloated packages for lean ones.</div>
</div>

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">🧑‍🔬</div>
  <div class="font-bold text-orange-400 text-sm mb-1">Visualize Trees</div>
  <div class="text-xs text-gray-400">Use <a href="https://npmgraph.js.org" class="underline text-orange-300">npmgraph</a> to show devs their actual dependency tree — make the abstract visible.</div>
</div>

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">📋</div>
  <div class="font-bold text-yellow-400 text-sm mb-1">Make it a Security KPI</div>
  <div class="text-xs text-gray-400">Track dep count, unused deps, and outdated packages in quarterly reviews.</div>
</div>

<div v-click class="bg-gray-800/60 rounded-xl p-5 border border-gray-700">
  <div class="text-3xl mb-2">🏆</div>
  <div class="font-bold text-red-400 text-sm mb-1">Celebrate Wins</div>
  <div class="text-xs text-gray-400">Show before/after. <span class="text-red-300">Brag about removals.</span> Make reduction visible and rewarding.</div>
</div>

</div>

<div v-click class="mt-8 p-5 bg-gradient-to-r from-blue-900/30 via-purple-900/30 to-red-900/30 rounded-xl border border-gray-600">
  <div class="text-xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-purple-400 to-red-400">
    Security isn't just about adding controls — it's about removing risk.
  </div>
  <div class="text-sm text-gray-400 mt-2">
    Every dependency removed is a CVE that will never need a patch.
  </div>
</div>

<!--
This is the key message I want to leave you with.

Security professionals often think in terms of ADDING controls:
- Add a firewall
- Add a scanner
- Add a policy

But sometimes the most effective security intervention is REMOVAL.

By championing tools like knip and e18e, you:
- Reduce attack surface
- Reduce maintenance burden
- Reduce CVE exposure
- Build trust with dev teams (you're helping them, not blocking them)

The best part? Devs already want to do this. They just need permission and tools.
Security can provide both.

Remember: The most secure dependency is the one you don't have.
-->
