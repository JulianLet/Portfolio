---
title: 'Echoes of the Masquarade'
description: 'Verticle Slice Project'
pubDate: 'Jun 06 2025'
heroImage: '/src/assets/04_EoM/00_Logo.jpg'
---

<!-- summery -->
This game was part of our Vertical Slice course. It is a **rouge-like action game** based around music and Italian folklore. We got ten weeks to be able to develop our dream game full time. We even got our own office spaces. Our project owner was a ver passionate Italian who came up with the idea for the game.

<!-- links -->
We got to display this project at the <a href="https://game.speldesign.uu.se/projects/3d-games/echoes-of-the-masquerade/" target="_blank" rel="noopener noreferrer">Gotland Game Conference 2025</a>.

Get this game on <a href="https://cristian-de-santis.itch.io/echoes-of-the-masquerade" target="_blank" rel="noopener noreferrer">itch.io</a>. Only playable on windows.

<!-- my focus -->
For this project my focus was on developing a **tilable world generation system**. We wanted to have a semi random map every time the player started a new game. So we created different variations of chambers and path tiles which were then instanciated when the player started the game. This is done my applying an _A* algorithm_ to connect the generated chambers with each other and filling the generated paths with the appropiate path tiles.

<figure class="center">
  <img src="../../assets/04_EoM/01_WorldGenTest.png" alt="worldgentest" width="800" />
  <figcaption>Prototype of Level Generation in Visual Studio using Raylib</figcaption>
</figure>

<figure class="center">
  <img src="../../assets/04_EoM/02_WorldGenUnity.png" alt="worldgenunity" width="800" />
  <figcaption>Level Generation in Unity</figcaption>
</figure>

<figure class="center">
  <img src="../../assets/04_EoM/03_ChamberVariation.png" alt="chamber variations" width="800" />
  <figcaption>Sample of Chamber Variations with fountain</figcaption>
</figure>

Next to the world generation I also added a **modular charm system** to apply buffs to the player. The game design was asking for a lot of different charms so my idea was to make the individual buffs as extra componentns which can then be combined to the needs of the specific charm. This simplefied the variety for the differnet charms and made the creation of new ones quick and straightforward.

<div class="grid-gallery">
  <img src="../../assets/04_EoM/04_WineChaliceGDD.png" alt="gdd" />
  <img src="../../assets/04_EoM/05_WineChalicePrefab.png" alt="prefab" />
</div>
<figure class="center">
  <figcaption>Example of the modular charm setup</figcaption>
</figure>

Another focus I had was the creation of the **enemy and boss AI**. The enemies and the boss had specific behaviours depending on player position and the current state of the other enemies that were close.


<div class="center">
  <video controls width="600">
    <source src="../../assets/04_EoM/07_AttackSchemes.mp4" type="video/mp4" />
  </video>
    <figcaption>Different attack behaviours for Mommotti and Pulchinella</figcaption>
</div>

<!-- reflection -->
As I have been working in a real working environment full time in a team, being back in an office and working alongside you collegues made me realise how much I missed that. Being close to your collegues adds so much more than just shorter communication paths. The laughs in the office, the chats, but also the inspiration of having someone working next to me makes it so much more productive. Again I had the privilege to work with an amazing team with passionate developers. Working in an office also helped me get insights into how the process is for 3D assets, how much time they need to be created and how animations are done. This is also something that is amazing to me. When the game turns from my gray and red boxes to a great looking game.

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