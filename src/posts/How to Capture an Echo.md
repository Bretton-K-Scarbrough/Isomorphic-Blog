---
title: The Shape of a Room
description: An exploration of how Green's functions can be utilized to capture a room's echo and put it onto an audio signal. 
date: '2024-3-??'
categories: 
    - Differential Equations
    - Signal Processing
    - Music 
published: true
---

<script>
    import Katex from 'svelte-katex'
</script>
<svelte:head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.13.13/dist/katex.min.css" integrity="sha384-RZU/ijkSsFbcmivfdRBQDtwuwVqK7GMOw6IMvKyeWL2K5UAlyp6WonmB8m7Jd0Hn" crossorigin="anonymous">

</svelte:head>
## 
Have you ever been singing in the shower and had the thought: "Man, I sound way better in the bathroom than anywhere else..." 

## Brief Introduction to Green's Functions
Most people are familiar with what an inverse operation is. It is an operation that undoes whatever the original operation did. An elementary example is multiplication and division. 
<br>

Take a variable <Katex>x</Katex> and multiply it by some constant <Katex>a \\in \\mathbb'{'h'}'</Katex> 
<Katex displayMode>a \cdot x = b</Katex>
<Katex displayMode>ax = b</Katex>
