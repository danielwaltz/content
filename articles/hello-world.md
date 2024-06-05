---
date: 2024-06-02
status: published
---
# Hello World

This is a test for writing article content to be consumed by other sources.

```vue
<script setup lang="ts">
const foo = ref('bar');
</script>

<template>
  <div>{{ foo }}</div>
</template>
```

This is a change.

I have some interest in starting to write blog posts and content about my experience as a developer and sharing some of the things I have learned in my career.

The biggest hurdle I have faced is finding the right platform and tools for me to write without feeling blocked or having barriers. One avenue I am exploring for this is using Obsidian to author my content in plain markdown files, automatically syncing this content with a public GitHub repository, and using this repo to fetch and display the content wherever I want!

As I am most familiar with Nuxt and its ecosystem of modules, the official Nuxt Content module seemed like a great fit. With a small amount of configuration I was able to wire up to my public repo, query for content that fit in expected parameters, and quickly style the content however I liked.