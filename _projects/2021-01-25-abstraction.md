---
title: An AI Parasite Detection System
date: 2021-01-25 08:01:35 +0300
subtitle: AI
image: '/images/project-1.jpg'
---

In this project I created an automatic system for detect parasites in videos. At the core of this system, there is a Transformer (Detection Transforer: DeTr) that analizes the videos. 
<div class="gallery-box">
  <div class="gallery">
    <img src="/images/project-5.jpg" alt="Project">
    <img src="/images/project-8.jpg" alt="Project">
    <img src="/images/project-6.jpg" alt="Project">
  </div>
  <em>Projects / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

The idea is quite simple: 

i) Our users make a fecal sample of the animal they want to test. /n
i) They send a video of that sample to our servers. /n
ii) In our servers we deploy DeTr to analyze these videos. /n
iv) After this, our users receive a summary of the analyses. /n


<p><iframe src="https://www.youtube.com/embed/Uc96-OZE460?si=sKArgRBAkS6lS401" frameborder="0" allowfullscreen></iframe></p>

The summary tells our users whether theirs animals areinfected,and if so, which parasites were detected.

