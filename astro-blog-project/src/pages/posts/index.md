---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: My first blogpost!
publishDate: 12 Sep 2021
name: Sandra Mago
value: 128
description: Welcome to my blog.
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Hey there
<br> This is my blog! 
