---
title: 'Shadertoy Clone'
description: 'Real time graphics project'
pubDate: 'Jan 17 2025'
heroImage: '/public//assets/02_Shadertoy/00_Logo.png'
---

<!-- summery -->
This was my final project of the Real-Time graphics course. This was a 70 hour project to explore a topic that we could choose freely. I set up an environment from scratch, following a tutorial by the youtuber "The Cherno", to enable shader code programming and then created different examples for it.

<!-- links -->
Take a look on <a href="https://github.com/JulianLet/ShadertoyClone" target="_blank" rel="noopener noreferrer">github</a>

<!-- my focus -->
I created a **shader writing system** in _Visual Studio 2022_ using _c++_. I set up the basic essentials with vertex buffers, frame buffers and index buffers. I also added the imgui environment to help me set up a testing platform to quickly switch between different examples I have created. I then created different shader examples from displaying a basic disc over light reflection on a plane to animated shaders similar to those found on shadertoy.com. 

<figure class="center">
  <img src="/assets/02_Shadertoy/01_LightTest.gif" alt="Light" width="800" />
  <figcaption>First test with reflection</figcaption>
</figure>

<figure class="center">
  <img src="/assets/02_Shadertoy/02_AnimatingTest.gif" alt="Animated" width="800" />
  <figcaption>Animated shader from shadertoy</figcaption>
</figure>

<figure class="center">
  <img src="/assets/02_Shadertoy/03_HeartTest.gif" alt="Heart" width="800" />
  <figcaption>Animated Heart</figcaption>
</figure>

<!-- reflection -->
I enjoyed this project a lot. As we were able to to freely choose what kind of project we want to do and we did not cover shader code programming during the course I choose this project. We only covered how the render pipeline works and what is happening in a very abstract way, it was hard for me to understand. This project helped me so much in understanding what shaders are, how they work and how they can be written. It also helped me in understanding more and more in how to set up big systems and working environments. How to structure code and how coding architecture works. 

<style>
.grid-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  justify-items: center; /* centers each image in its grid cell */
}
.center {
  text-align: center; /* horizontally centers inline elements like img */
}
.center img {
  display: inline-block; /* ensures image respects centering */
}
figure {
  margin: 1rem 0;
}
figcaption {
  font-size: 0.9rem;
  color: #666;
  text-align: center;
}
</style>