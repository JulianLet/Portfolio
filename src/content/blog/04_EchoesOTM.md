---
title: 'Echoes of the Masquarade'
description: 'Vertical Slice Project'
pubDate: 'Jun 06 2025'
heroImage: '/public/assets/04_EoM/00_LogoSq.PNG'
bannerImage: '/public/assets/04_EoM/00_Logo.png'
---

<!-- summary -->
This game was part of our Vertical Slice course. It is a **rogue-like action game** based around music and Italian folklore. We had ten weeks to develop our dream game full-time within our own office spaces. Our project owner was a very passionate Italian who pitched the idea for the game.

<!-- links -->
This project was showcased at the <a href="https://game.speldesign.uu.se/projects/3d-games/echoes-of-the-masquerade/" target="_blank" rel="noopener noreferrer">Gotland Game Conference 2025</a>.

Get this game on <a href="https://cristian-de-santis.itch.io/echoes-of-the-masquerade" target="_blank" rel="noopener noreferrer">itch.io</a>. Only playable on Windows.

<!-- my focus -->
For this project, my focus was on developing a **tileable world generation system**. We wanted a semi-random map each time the player started a new game. To achieve this, we created different variations of chambers and path tiles, which were then instantiated at the start of the game. An _A* algorithm_ was used to connect the generated chambers, and the generated paths were filled with the appropriate path tiles.

<figure class="center">
  <img src="/assets/04_EoM/01_WorldGenTest.png" alt="worldgentest" width="800" />
  <figcaption>Prototype of Level Generation in Visual Studio using Raylib</figcaption>
</figure>

<figure class="center">
  <img src="/assets/04_EoM/02_WorldGenUnity.png" alt="worldgenunity" width="800" />
  <figcaption>Level Generation in Unity</figcaption>
</figure>

<figure class="center">
  <img src="/assets/04_EoM/03_ChamberVariation.png" alt="chamber variations" width="800" />
  <figcaption>Sample of Chamber Variations with fountain</figcaption>
</figure>

In addition to world generation, I also added a **modular charm system** to apply buffs to the player. The game design required many different charms, so I designed individual buffs as separate **components**, which could then be combined to form specific charms. This simplified the variety of charms and made creating new ones quick and straightforward.

<div class="grid-gallery">
  <img src="/assets/04_EoM/04_WineChaliceGDD.png" alt="gdd" />
  <img src="/assets/04_EoM/05_WineChalicePrefab.png" alt="prefab" />
</div>
<figure class="center">
  <figcaption>Example of the modular charm setup</figcaption>
</figure>

Another focus I had was the creation of the **enemy and boss AI**. The enemies and the boss had specific behaviors that depended on the player’s position and the state of nearby enemies. The Mommotti, the regular enemy encountered during the level, has a passive attack behavior: they circle the player and only attack individually. In contrast, the boss is very aggressive, spamming different attacks depending on the player’s position.

<figure class="center">
  <iframe 
    width="640" 
    height="360" 
    src="https://www.youtube.com/embed/VI0uthSYkag" 
    title="Different attack behaviours for Mommotti and Pulchinella" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
  </iframe>
  <figcaption>Different attack behaviours for Mommotti and Pulchinella</figcaption>
</figure>

<!-- reflection -->
Having previously worked full-time in a professional environment, being back in an office and collaborating closely with colleagues reminded me how much I missed that. Being physically close adds more than just shorter communication paths—it brings inspiration, quick feedback, and a more productive workflow. I had the privilege of working with an amazing team of passionate developers. Being in the office also gave me insight into the creation of 3D assets, the time required to produce them, and how animations are implemented. It was incredible to see the game transform from my gray and red placeholder boxes into a fully realized, visually appealing experience.