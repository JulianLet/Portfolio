---
title: 'Wind Riders'
description: 'First year Arcade game'
pubDate: 'May 31 2024'
heroImage: '/src/assets/01_WindRiders/00_Logo.png'
---

<!-- summery -->
To finish our first year of our Game Design programm we had our first production course. Our task was to create an _Arcade game_ and develop an unconventional input. We created a sailing racing game in _Unity_, themed around vikings to embrace our Nordic connection. We created an arcade booth looking like a small sailing boat. The player sit inside with one hand on the rudder, to stear the boat, and the other on a rope to turn a sail adjusting it to the wind direction.

<!-- links -->
We got to display this project at the <a href="https://game.speldesign.uu.se/projects/arcade-games/wind-riders/" target="_blank" rel="noopener noreferrer">Gotland Game Conference 2024</a> where it was awarded **the Jury Spotlight Award**.

Play this game on <a href="https://julianletsche.itch.io/wind-riders" target="_blank" rel="noopener noreferrer">itch.io</a>

<!-- my focus -->
In this project my focus was on the **physics system**, on how the sail cought the wind and pushed the boat. I was also in charge of setting up the **custom input system**. We used two computer mice and split their vertical and horizontal movement input. The mice were attached to the shafts of the rudder and sail, and moving them was simulating the mouse moving over the table which we then translated inside the game.  

<figure class="center">
  <img src="../../assets/01_WindRiders/02_Gameplay.gif" alt="Gameplay" width="800" />
  <figcaption>Gameplay</figcaption>
</figure>

<figure class="center">
  <img src="../../assets/01_WindRiders/03_InputConcept.png" alt="Input" width="800" />
  <figcaption>Concept of Custom Input</figcaption>
</figure>


Another big aspect I was focusing on was the **enemy AI** which the player was racing against. The way I set it up was that there were checkpoints on track which the AI used to follow the track. The precision in which the AI was stearing and adjusting the sail was varied to set different difficulties on the different tracks.

<!-- grid -->
<div class="grid-gallery">
  <img src="../../assets/01_WindRiders/04_AICheckpoints.png" alt="LevelOne" />
  <img src="../../assets/01_WindRiders/05_AISettings.png" alt="Spawner" />
</div>

<!-- reflection -->
This project did a lot to me. From the amazing team I had, to the hours in the workshop building the booth as well as the realisation that Game Design programming does not need to be with controller or keyboard inputs. And all this work being rewarded with winning an award made it all worth so much more.

<figure class="center">
  <img src="../../assets/01_WindRiders/Elias.JPEG" alt="Input" width="800" />
</figure>

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