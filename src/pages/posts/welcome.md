---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 12 Sep 2021
name: Brandon Jones
value: 128
description: First post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />
