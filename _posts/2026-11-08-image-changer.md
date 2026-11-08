---
title: "Image Changer"
date: 2025-12-10 00:00:00 +1100
categories: [Computer Science, Low-Level Programming]
tags: [mips, assembly, image-processing]
description: "A MIPS assembly assignment implementing image manipulation and compression operations."
featured: true
image: /assets/lib/posts/image_changer/cat.png
---

## Overview

For this assignment, I wrote code to modify different aspects of an image. The supported operations included adjusting brightness, changing colour, and converting an image to grayscale. The assignment also involved compressing and decompressing images.

## Image Processing

The program modifies image data to produce different visual results.

<!-- Add the exact operations supported and explain how pixel data is represented. -->

## Implementation

I used **MIPS assembly language** to complete the assignment. Working at this level made the task challenging, but it was rewarding to get the image operations working.

## What I Learned

The assignment gave me practical experience with MIPS assembly and a better understanding of how image data can be manipulated and processed at a low level.

## Project Gallery

{% capture gallery %}
<div class="slide">
  <img src="/assets/lib/posts/image_changer/cat.png">
  <div class="description">
    The default image
  </div>
</div>

<div class="slide">
  <img src="/assets/lib/posts/image_changer/cat-compressed.png">
  <div class="description">
    compressed version of the cat
  </div>
</div>

<div class="slide">
  <img src="/assets/lib/posts/image_changer/cat-gray8.png">
  <div class="description">
    using the grayscale filter
  </div>
</div>
{% endcapture %}

{% include slideshow.html content=gallery %}
## Further Details
View the source code on [GitHub](https://github.com/Yuxiang-He-NZ/COMP1521/tree/main/ass2).