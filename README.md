![](ClickBOOMTitle.png)

<br />

![Project Type](https://custom-icon-badges.demolab.com/badge/Project%20Type-Personal-F25278?style=for-the-badge&logo=file&logoColor=white) ![C#](https://custom-icon-badges.demolab.com/badge/Language-C%23-brightgreen?style=for-the-badge&logo=command-palette&logoColor=white) ![App Type](https://custom-icon-badges.demolab.com/badge/Application%20Type-Game-blue?style=for-the-badge&logo=terminal&logoColor=white) ![Game Engine](https://custom-icon-badges.demolab.com/badge/Game%20Engine-Unity-purple?style=for-the-badge&logo=controller&logoColor=white)

<details open> 
<summary><h2>🗒️ Project Description</h2></summary>

<br />
Click-BOOM! is a game created as a fun project/learning experience involving the player strategically purchasing and igniting fireworks in order to get their score as high as possible with a limited number of clicks. Show off your skills of timely and limited ignitions and accuracy, buy multiple different unique fireworks (all with their own challenges), upgrade your abilities, and ignite the sky with a fireworks show that will be remembered for the rest of time!

<br /><br />This project was created to familiarize myself with aspects of rapid prototyping and UI/UX development.
Some aspects of this project include:
  - Utilization of the concept of tweening (animation through code) in order to create a user-friendly and eye-catching interface while also minimizing performance impacts without relying on Unity's animation system.
  - Gameplay balancing and complex progression system development
  - Basic implementation of an online leaderboard API for keeping track of player scores

There are some additional elements that were a part of this project, such as utilization of render textures to create a pixel perfect art-style, powerups, and basic multi-scene management within Unity.

<br />

<h2>⬇️ Completed Project Download</h2>
This project is fully playable and available on my itch.io page! <br />
It can be viewed and downloaded here: https://coba-platinum.itch.io/click-boom

<br /><br />

*Coba Platinum is an alias that I have used since highscool when releasing anything to the public!

<br />

<h2>📦 Project Repository</h2>
This project is fully available in this repository!
</details>

<br/>

<p float="left">
  <img src="Screenshots/Screenshot_2560x1440_004.png" width="49%" />
  <img src="Screenshots/Screenshot_2560x1440_005.png" width="49%" />
</p>
<p float="left">
  <img src="Screenshots/Screenshot_2560x1440_006.jpg" width="49%" />
  <img src="Screenshots/Screenshot_2560x1440_007.png" width="49%" />
</p>

<details open> 
<summary><h2>🛠️ Tools Used</h2></summary>

<br />

<img align="center" alt="Unity" width="40px" style="padding-right:10px;padding-bottom:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/unity/unity-original.svg"/> [Unity] - Primary Game Engine

<img align="center" alt="Git" width="40px" style="padding-right:10px;padding-bottom:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/> [Git] - Source Control

</details> 

<br />

<p float="left">
  <img src="Screenshots/Screenshot_2560x1440_001.jpg" width="49%" />
  <img src="Screenshots/Screenshot_2560x1440_002.png" width="49%" />
</p>
<p float="left">
  <img src="Screenshots/Screenshot_2560x1440_003.png" width="49%" />
  <img src="Screenshots/Screenshot_2560x1440_008.png" width="49%" />
</p>
<p float="left">
  <img src="Screenshots/Screenshot_2560x1440_009.png" width="49%" />
  <img src="Screenshots/Screenshot_2560x1440_010.jpg" width="49%" />
</p>
<p align="center">
  <img src="Screenshots/Screenshot_2560x1440_011.png" width="49%" />
</p>

<details open> 
<summary><h2>🧠 Project Reflection</h2></summary>

- **How would you describe the process of creating and polishing the artifact?**
  
I feel that creating and polishing this artifact was very enjoyable and challenging, as I had to learn a completely different game architecture to create a fun and engaging multiplayer experience. I started with a basic idea of what I wanted to do, which was a multiplayer version of the classic snake game, and began from there. I first created a singleplayer prototype of the game, allowing my to plan and develop the different game mechanics for the game, followed by implementing working multiplayer into the game. Though this is not the recommended method of creating a multiplayer game, as it takes a lot more work, it did allow me to get a full understanding of the differences between crafting a singleplayer and multiplayer experience from behind the scenes.
  
- **What did you learn as you were creating it and improving it?**

This project gave me a chance to learn the many systems and techniques that make a multiplayer game possible. I was able to gain knowledge with with different game-related multiplayer architectures, such as peer-to-peer, client-server, etc. and when their strengths and weaknesses for different play styles within a game. I was able to learn how clients communicate with the server, and vice versa, in order to sync the game state for all players, whether that be player locations, enemy locations, animations, player statistics, and more. Whilw working on this project, I had to completely rethink about how game logic clasically works within a singleplayer experience, as a lot of different implementations for one more than likely will not work for the other. I also gained experience with Unity's multiplayer tools, specifically netcode for game objects and their lobby system, in order to complete this project.

- **What challenges did you face?**

As mentioned in the previous section, majority of the challenges faced within the development of this game were related to having to completely rethink how the logic within a game should be implemented during development. Having to decide what information should be client-side vs server-side, what information should be only calculated on the clients, what information should be sent to/from the server, and more were all very challenging experiences in order to make a fully functional and optimized/effecient multiplayer game.

- **How could this artifact be improved?**

There are many different aspects of this project that I feel could be improved, but if I were to work on the project again, my top priority would probably be to swith the networking from a client-authoritative to a server-authoritative model. I initially decided to develop with a client-authoritative model due to the lower amount of complexity when developming and implementing the networking logic for the game, but this eventually led to some unintended consequences, especially wth collision detection for the different player characters (the snakes). Switching to a server-authoritative model where the player movement and collision is all calculated on the server and then synced to the connected clients would essentially solve a lot of the issues that I ended up encountering during the course of developing this project!
</details> 

<br />

<p align="center">
  <img src="LiamRandLogo.png" width="10%" />
</p>
