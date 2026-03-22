---
title: 'Wind Riders'
description: 'First year arcade game'
pubDate: 'May 31 2024'
heroImage: '/public/assets/01_WindRiders/00_Logo.png'
---

<!-- summary -->
To finish our first year, we had our first production course. Our task was to create an _Arcade game_ and develop an unconventional input. **Wind Riders** is a sailing racing game developed in _Unity_, themed around Vikings to embrace our Nordic connection. We created an arcade booth looking like a small sailing boat. The player sits inside with one hand on the rudder to steer the boat, and the other on a rope used to adjust the sail to the wind direction.

<!-- links -->
This project was showcased at the <a href="https://game.speldesign.uu.se/projects/arcade-games/wind-riders/" target="_blank" rel="noopener noreferrer">Gotland Game Conference 2024</a> where it was awarded **the Jury Spotlight Award**.

Try this game on <a href="https://julianletsche.itch.io/wind-riders" target="_blank" rel="noopener noreferrer">itch.io</a>

<!-- my focus -->
In this project, my focus was on the **physics system**, specifically how the sail catches the wind to push the boat. I was also in charge of setting up the **custom input system**. We used two computer mice and split their vertical and horizontal input. The mice were attached to the shafts of the rudder and sail, and rotating them simulated mouse movement which we then translated into in-game input.  

<figure class="center">
  <video controls width="600">
    <source src="/public/assets/01_WindRiders/02_Gameplay.mp4" type="video/mp4" />
  </video>
  <figcaption>Gameplay</figcaption>
</figure>

<figure class="center">
  <img src="/assets/01_WindRiders/03_InputConcept.png" alt="Input" width="800" />
  <figcaption>Concept of Custom Input</figcaption>
</figure>

Another big aspect I was focusing on was the **enemy AI** which the player was racing against. I implemented this by adding checkpoints on the track, which the AI used to follow. The precision with which the AI steered and adjusted the sail was varied to create different difficulty levels across tracks.

<!-- grid -->
<div class="grid-gallery">
  <img src="/assets/01_WindRiders/04_AICheckpoints.png" alt="AI checkpoints" />
  <img src="/assets/01_WindRiders/05_AISettings.png" alt="AI settings" />
</div>

<!-- reflection -->
This project meant a lot to me. From the amazing team I worked with, to the hours spent in the workshop building the booth, it showed me that game design programming does not have to rely on traditional controller or keyboard inputs. Seeing all this work rewarded with an award made it even more meaningful.

<figure class="center">
  <img src="/assets/01_WindRiders/Elias.JPEG" alt="Input" width="800" />
</figure>