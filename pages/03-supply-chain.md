---
transition: fade-out
---

# JS Supply Chain Attacks: A Recent Storm

<div class="grid grid-cols-2 gap-3 mt-3">

<div v-click class="bg-red-900/30 border-l-4 border-red-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-red-400">🔴 chalk + debug (Sep 2025)</div>
  <div class="text-xs text-gray-300 mt-1">18 popular packages compromised via phishing. <span class="text-red-300">2B+ weekly downloads</span> — crypto wallet theft in browsers. Detected in ~2 hours.</div>
</div>

<div v-click class="bg-orange-900/30 border-l-4 border-orange-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-orange-400">🪱 Shai-Hulud Worm (Sep 2025)</div>
  <div class="text-xs text-gray-300 mt-1"><span class="text-orange-300">First self-replicating npm worm.</span> 517+ packages compromised. Harvested creds via TruffleHog, auto-published malicious versions using stolen npm tokens.</div>
</div>

<div v-click class="bg-yellow-900/30 border-l-4 border-yellow-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-yellow-400">💀 Shai-Hulud 2.0 (Nov 2025)</div>
  <div class="text-xs text-gray-300 mt-1"><span class="text-yellow-300">25K+ GitHub repos exposed.</span> Fake Bun installer with 10MB obfuscated payload. Falls back to wiping your home directory if creds can't be stolen.</div>
</div>

<div v-click class="bg-purple-900/30 border-l-4 border-purple-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-purple-400">📡 Axios Compromise (Mar 2026)</div>
  <div class="text-xs text-gray-300 mt-1">Account takeover of lead maintainer. Attributed to <span class="text-purple-300">DPRK threat actors</span>. Malicious versions published via compromised CI/CD pipeline.</div>
</div>

<div v-click class="bg-blue-900/30 border-l-4 border-blue-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-blue-400">🔑 eslint-scope (2018)</div>
  <div class="text-xs text-gray-300 mt-1">npm token theft via compromised maintainer account. Malicious version <span class="text-blue-300">exfiltrated .npmrc credentials</span> from build machines. The blueprint for modern attacks.</div>
</div>

<div v-click class="bg-pink-900/30 border-l-4 border-pink-500 rounded-r-lg p-3">
  <div class="text-sm font-bold text-pink-400">🎯 S1ngularity / Nx (Aug 2025)</div>
  <div class="text-xs text-gray-300 mt-1">GitHub token stolen from CI. Attacker published malicious Nx packages. <span class="text-pink-300">Direct precursor to Shai-Hulud</span> — same stolen tokens used to kick off the worm.</div>
</div>

</div>

<div v-click class="mt-3 p-3 bg-gray-800/50 rounded-lg border border-gray-600 text-center">
  <span class="text-gray-200 text-sm font-semibold">This is not slowing down.</span>
  <span class="text-gray-400 text-xs block mt-1">Sonatype: 454k+ new malicious packages in 2025 (+75% YoY) — and every one entered through a dependency.</span>
</div>

<!--
These are just the headline-grabbing ones. Countless more happen every year.

Key takeaway: This is NOT a JavaScript problem. It's a software industry problem.

- SolarWinds: Attackers inserted backdoor into Orion build pipeline through compromised dependencies
- event-stream: Maintainer handed over package to attacker who added bitcoin-stealing code
- log4shell: Flaw in a widely-used Java logging library, every app transitive dependent was vulnerable
- xz-utils: Sophisticated years-long social engineering attack on Linux utility

The more dependencies you have, the more trust relationships you're managing.
-->
