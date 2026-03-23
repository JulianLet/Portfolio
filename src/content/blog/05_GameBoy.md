---
title: 'Game Engine'
description: 'Raspberry Pi Pico Game Engine'
pubDate: 'Mar 21 2026'
heroImage: '/public/assets/05_GameEngine/00_Logo.png'
bannerImage: '/public/assets/05_GameEngine/00_Logo.png'
keywords: "Visual Studio 2022, Raspberry Pi Pico W, System Programming, C++"
---

<!-- summary -->
This is my passion project: a **handheld game console** built with a Raspberry Pi Pico microcontroller. Inspired by playing Pokémon on my old GameBoy Color, I wanted a device that could run my own games. Using _Visual Studio Code_ with _C++_ and the Raspberry Pi Add-On, I’m building both the games and the underlying engine.

<figure class="center">
  <img src="/assets/05_GameEngine/01_photo.JPEG" alt="Table" width="800" />
</figure>

The engine is built around an **Entity-Component-System (ECS)** architecture for modularity and scalability. It already supports a physics engine, sprite sheets, animations, and a file system on the SD card. Working within the **strict hardware limits** of the Raspberry Pi Pico — very limited RAM and flash memory — forced careful management of assets, memory, and CPU usage. I designed a compact, efficient architecture that handles physics, input, rendering, and file management while keeping resource usage minimal.

<!-- links -->
Take a look at  <a href="https://github.com/JulianLet/RPi_GameEngine" target="_blank" rel="noopener noreferrer">GitHub</a>

<!-- my focus -->
This project taught me a lot about combining hardware and software in game development. Implementing an ECS, building a physics engine, and managing sprite sheets and file systems on an SD card helped me learn how to structure a large-scale, modular engine. Seeing my own games run on a custom handheld device is incredibly rewarding, and balancing functionality with strict memory and performance constraints has been one of the most technically challenging and satisfying aspects of the project.

The current prototype showcases several small games, including:
- A Pong clone  
- A Jump'n'Run demo  
- A tilemap/animation demo where the player can walk around a small area  

The next steps are to create full games for it. I still dream of making my own small version of Pokémon as well as other mini-games.

<figure class="center">
  <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/ejguey6CQ4o?si=sOuHgVjdww8q0kQI" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
  <figcaption>Pong</figcaption>
</figure>

<figure class="center">
  <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/CrplLZgiRWM?si=mkT5LVBQWs3sQRs_" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
  </iframe>
  <figcaption>Animation Demo</figcaption>
</figure>