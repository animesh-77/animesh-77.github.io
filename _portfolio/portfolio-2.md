---
title: "Guided project"
excerpt: "Detecting active fire regions from mutlispectral satellite images in <em>near real time</em><br/><img src='/images/active_fire.png' width='50%'>"
collection: portfolio
---

# Overview

This project served as my first exploration into the realm of deep learning, offering me a genuine introduction to the field after successfully creating a basic MNIST digit recognition program. *Why satellites?* I chose to work with satellite imagery due to my enduring fascination with all things related to space. Detecing active fires is an open problem and a scalable and reliable soltuion can save millions of dollars every year.

<figure>
  <img src="/images/active_fire.png" alt="Forest fire from Landsat-8" style="width:100%">
  <figcaption>Forest fire as seen from Landsat-8 <em>Credits: USGS  </em></figcaption>
</figure>

I chose Landsat-8 since it provides global coverage, has a short revisit frequency and most importantly a resolution of 30 metres in 7 bands. And it is entirely free !! I implemented a U-Net based encoder-decoder model for semantic segmentation of active fire *pixels* in an image.

Developing a pipeline of this scale meant I had to get learn (and follow) good coding practices, Git for version control and keep my code well documented (something I could never learn from Leetcode &#128517;). 