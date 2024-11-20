---
date: 2024-06-04T20:00:00
status: published
---
# Hello World

My plan for attempting to begin a path of writing; ideas for keeping me from feeling friction when authoring, free from being locked in to a specific service or set of tools, and of course the first step after getting set up... writing the post you're reading right now!
## Why?

I have had some interest in writing blog posts and content about my experiences as a developer and sharing some of the things I have learned in my career for many years now. While I could attribute the majority of the reason for why I haven't started down this path before to laziness (a very common and arguably beneficial trait for developers), I have also wrestled with imposter syndrome and consumed so much from other authors and developers that I admire (and crediting them absolutely deserves a post by itself) that I never *truly* ever felt like it's a space I could meaningfully contribute to.

What changed now? Frankly, I can't say it's any specific event or moment. I've been working in the development industry for [15 years](https://www.linkedin.com/in/danielbwaltz/) now, so perhaps it's just my time. 😆 And honestly, in this age of explosive generative AI growth, it almost feels like now might be about the *worst* time to start exploring hand-authoring text based content. But hey, someone's still gotta feed the machine right? So here we are!

I feel some excitement to start dipping my toes in this, but another aspect that really gnawed at me is finding the right platform and tools for me to write without feeling blocked, locked in, or having barriers to actually start writing. So obviously, as a developer, this was the path that I had to explore first! <sup>heh</sup>
## How?

I had a high level idea for what I wanted:

1. Simple file based content using markdown `.md` for longevity and scripting ability
2. Able to use publicly available services and zero cost software (ideally open source)
3. Content lives separately from where it is consumed
4. Full rich text editor experience
5. A workflow that is as simple as "save file → see content"

You might be thinking, as I sure was as I was theorizing this plan, that this doesn't sound simple at all. 👀 Honestly... you would be right. I can joke and say that this is just the *way of the developer™️*, but in reality this is what I really felt was required for me to actually start writing. If it's as simple as opening an app on my Mac, creating a new file, and writing, what excuses do I have left?

As fate would have it, late one night a spark of inspiration hit. I had a vague familiarity with an application called [Obsidian](https://obsidian.md/) after briefly using Notion at my job and going down a rabbit role after really enjoying the experience. I had read somewhere that it was *mostly* markdown based, which fit my first criteria of authoring my content in plain markdown files perfectly. Check!

After downloading it I discovered a vibrant community marketplace and spotted a [community plugin](https://github.com/denolehov/obsidian-git) that enables you to connect with and automatically sync your content to a [public GitHub repository](https://github.com/danielwaltz/content). This then triggered a memory of my framework of choice at the moment [Nuxt](https://nuxt.com/) having a content module that can [pull from external GitHub repos](https://content.nuxt.com/get-started/configuration#sources) for content with the ability to query and style content pretty much however you want. So I integrated it in my [personal website](https://github.com/danielwaltz/daniel-waltz) 👋 and wired everything up and bingo bingo presto!

## Wait... really?

Actually, yes! I absolutely thought there would be a catch (especially the connection between Nuxt and my GitHub repo), but truly it ended up being that simple. No doubt using a public repo made things much easier for lack of requiring authentication, but still. This was exciting to me, and this simplicity is exactly what drew me to using Nuxt in the first place!

If you're curious about how this is implemented and maybe want to try this out for yourself, the source code for my website is available [here](https://github.com/danielwaltz/daniel-waltz)! Plus, if you would like to see specifically the changes were required when adding this to an existing Nuxt project, check out [this commit](https://github.com/danielwaltz/daniel-waltz/commit/adbe60e2b95e3a77875fe2da5e5f5e0b4b40e941#diff-5977891bf10802cdd3cde62f0355105a1662e65b02ae4fb404a27bb0f5f53a07) in particular.

So consider this a practice run. The first (and maybe also the last) post I have ever written. Thanks for reading!