---
title: 'Big Wiz`'
description: "First year Shoot `em up game"
pubDate: 'Mar 21 2024'
heroImage: '/public/assets/00_BigWiz/00_Logo.png'
---

<!-- summery -->
This project was part of our Game Design 2 course where we were asked to create a **Shoot 'em up game**. At the start of the course each random assigned group got a initial theme for their project. Our was _Toxic Workplace_, which led to us choosing a coorperate building as a setting. The protagonist is the evil wizard boss who has to fight against the unionized workers.

<!-- links -->
Play this game on <a href="https://julianletsche.itch.io/bigwiz" target="_blank" rel="noopener noreferrer">itch.io</a>

<!-- my focus -->
In this project we were two programming students colaborating. My focus was on the **inventory and crafting system**. Defeated enemys dropped items which the player could use to craft new spells to unlock stronger attacks. 

<figure class="center">
  <img src="/assets/00_BigWiz/01_Crafting.gif" alt="Crafting" width="800" />
  <figcaption>Crafting and Inventory</figcaption>
</figure>

<figure class="center">
  <img src="/assets/00_BigWiz/02_Spells.gif" alt="Spells" width="800" />
  <figcaption>Using Spells</figcaption>
</figure>

For the final version of the game I was also in charge of creating the **level design**. That included level layouts, as well as setting up the enemy spawners. One aspect I remember to be challenging was, as we chose a diagonal perspective, the layering between the sprites.

<!-- grid -->
<div class="grid-gallery">
  <img src="/assets/00_BigWiz/04_LevelLayoutTwo.png" alt="LevelOne" />
  <img src="/assets/00_BigWiz/05_SpawnerSetup.png" alt="Spawner" />
</div>

<!-- reflection -->
This was my first bigger _Unity_ project and, looking back I am very happy on how it turned out. Considering we were in the second semester of our game design programm and I have only been programming for four month. With the knowledge I have now there has to be said that we choose a very ambishos goal. Having four different enemies, ten levels and ten different spells led to us neglegting some aspects like decorating the levels. But I am so pleased that we managed to finish this project and got lots of positive feedback for it. 

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