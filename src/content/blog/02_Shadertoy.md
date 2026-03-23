---
title: 'Shadertoy Clone'
description: 'Real time graphics project'
pubDate: 'Jan 17 2025'
heroImage: '/public/assets/02_Shadertoy/00_Logo.png'
bannerImage: '/public/assets/02_Shadertoy/00_Logo.png'
keywords: "Visual Studio 2022, OpenGL, System Programming, C++, Shader Programming"
---

<!-- summary -->
This was my final project of the Real-Time graphics course. We were asked to complete a 70-hour project exploring a topic of our choice. I set up an environment from scratch, following a <a href="https://www.youtube.com/playlist?list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2" target="_blank" rel="noopener noreferrer">tutorial series by the YouTube creator The Cherno</a>, to build an _OpenGL_-based environment for shader programming.

<!-- links -->
Take a look at <a href="https://github.com/JulianLet/ShadertoyClone" target="_blank" rel="noopener noreferrer">GitHub</a>

<!-- my focus -->
I created a **shader writing system** in _Visual Studio 2022_ using _C++_ and _OpenGL_. I set up the basic essentials with vertex buffers, frame buffers, and index buffers. I also added ImGui to create a testing platform where I could quickly switch between different shader examples. I then created several shader examples, ranging from rendering a basic disc to light reflections on a plane, and animated shaders inspired by shaders commonly found on Shadertoy.

<figure class="center">
  <iframe 
    width="640" 
    height="360" 
    src="https://www.youtube.com/embed/410L5bV0WDo" 
    title="First test with reflection" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
  </iframe>
  <figcaption>First test with reflection</figcaption>
</figure>

<figure class="center">
  <iframe 
    width="640" 
    height="360" 
    src="https://www.youtube.com/embed/nQu7iXVULC0" 
    title="Animated shader inspired by Shadertoy" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
  </iframe>
  <figcaption>Animated shader inspired by Shadertoy</figcaption>
</figure>

<figure class="center">
  <iframe 
    width="640" 
    height="360" 
    src="https://www.youtube.com/embed/QTbCy-UyXTA" 
    title="Animated Heart shader" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
  </iframe>
  <figcaption>Animated Heart shader</figcaption>
</figure>

<!-- reflection -->
I enjoyed this project a lot. As we were able to freely choose our project topic, I decided to explore shader programming, which was not covered during the course. We only covered how the render pipeline works and what is happening in a very abstract way. This made it hard for me to understand. This project helped me understand what shaders are, how they work, and how they can be written. It also improved my understanding of how to structure larger systems and development environments, as well as how to structure code and design software architecture.