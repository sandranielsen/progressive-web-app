---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Cheese
publishDate: 12 Sep 2021
name: Sandra Mago
value: 128
description: I love cheese
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Hey there
<br> Today's blog is going to be all about my favourite food!
<br> Cheese
<br> I like it so much that I actually managed to finish one whole triangle of parmesan cheese within a week :O

