---
layout: center
transition: slide-left
class: text-center
---

# Storybook: The Cleanup

<div class="flex justify-center gap-6 mt-6">
  <div v-click class="bg-red-900/20 rounded-lg p-5 border border-red-500/30 max-w-sm">
    <div class="text-lg font-bold text-red-400 mb-3">Storybook 7 → 8</div>
    <div class="font-mono text-sm text-gray-400 leading-relaxed text-left">
      node_modules/<br>
      ├── @storybook/react<br>
      ├── @storybook/addon-essentials<br>
      ├── @storybook/builder-vite<br>
      ├── @storybook/core-server<br>
      ├── webpack<br>
      ├── webpack-dev-middleware<br>
      ├── fork-ts-checker-webpack-plugin<br>
      ├── react-docgen-typescript<br>
      ├── csf-tools<br>
      ├── telejson<br>
      ├── ...<br>
      <span class="text-red-400 font-bold text-lg">~1,500+ transitive packages</span>
    </div>
  </div>

  <div v-click class="bg-green-900/20 rounded-lg p-5 border border-green-500/30 max-w-sm">
    <div class="text-lg font-bold text-green-400 mb-3">Storybook 9</div>
    <div class="font-mono text-sm text-gray-400 leading-relaxed text-left">
      node_modules/<br>
      ├── @storybook/react<br>
      ├── @storybook/addon-essentials<br>
      ├── @storybook/core<br>
      ├── ...<br>
      <span class="text-green-400 font-bold text-lg">~70% fewer dependencies</span>
    </div>
    <div class="text-xs text-gray-500 mt-3">by dropping deprecated packages, removing redundant layers, consolidating core</div>
  </div>
</div>

<div v-click class="mt-8 text-sm text-gray-400">
  ⚡ From ~1,500+ transitive packages to just a fraction — all while gaining features
</div>

<!--
Storybook is a great example because they went through this publicly.

The Storybook team did an audit of their dependency tree for version 9
- Dropping webpack 4 support (removed tons of legacy loaders)
- Consolidating into @storybook/core
- Removing deprecated APIs and their associated packages
- Dropping redundant dependencies

Next slide: Let me show you what this looks like visually.
-->
