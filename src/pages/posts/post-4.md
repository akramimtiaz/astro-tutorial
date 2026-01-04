---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'My Fourth Blog Post'
pubDate: 2022-08-08
description: "This post will show up on it's own"
author: 'Astro Learner'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "successes"]
---
This post should show up with my other blog posts, because `import.meta.glob()` is returning a list of all my posts in order to create my list.