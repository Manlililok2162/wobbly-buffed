# Game Design

<show-structure for="chapter,procedure" depth="2"/>

## Introduction

Video game ideas can come from personal experiences or existing games to which you think you can put a fun twist.

![Chess 960](https://static-assets.codecademy.com/Courses/intro-to-game-dev/design/intro/assets/chess960.jpeg)

The chess grandmaster Robert "Bobby" Fischer proposed a variant of chess called "Chess 960," which sought to reduce
memorizing of starting moves by randomizing the locations of the pieces.

## Game Type 🪜

To start, consider the type of your game before defining its rules or sketching its art. Most games classify as one of
the following:

* **Platformer:** A player controls a character that runs and jumps on platforms and avoids obstacles.
* **Multiplayer online battle arena (MOBA):** Players face one another in an arena-style environment.
* **Sports:** It resembles an existing sport or a made-up one.
* **Role-playing game (RPG):** The player assumes a fictional character in a story.
* **Puzzle:** The player solves problems, puzzles, and challenges.
* **Strategy:** It consists of a slower and sometimes turn-based gameplay requiring lots of thinking.
* **Action/adventure:** The player solves quests or missions in a high-paced environment.

## Player Experience 😀

In game design, consider a user experience where the player enjoys playing. Consider the following to do so.

1. **Emotion:** Be mindful of the emotions you want your players to experience. When winning, do you want them to feel
   good or play again? Otherwise, do you want them to try again when losing?
2. **Challenge:** Make your game reasonably challenging. An easy game may bore them, while a hard one may frustrate them
   too much to continue.
3. **Preference**: Consider the demographic of your game, including the age, culture, and preferences of the player.

## Game Objectives 🎯

Make the end goal to be accomplished by the player. Most goals and sub-goals include the following:

* Complete a challenge in the fastest way possible (_time-based_, _puzzle_, _strategy_).
* Beat a hard boss to advance the player to the next level (_action/adventure_).
* Find a hidden item to unlock more content, powers, or accessories (_action/adventure_, _RPG_).
* Complete a side quest that encourages exploration and world building (_action/adventure_, _RPG_).
* Score the most points (_sports_).

In Pokémon Sword and Shield, you ought to defeat all the gym leaders and become the champion. Meanwhile, you can
complete your Pokédex by catching and collecting Pokémon.

![A player battles Landorus as an optional objective](https://static-assets.codecademy.com/Courses/intro-to-game-dev/design/objectives/pokemon.png)

<note>Remember to match your objective with the player experience and the theme of the game.</note>

### Exercise: Game Objectives

In Codey's Adventure, do you recognize the main objective? Is it only one? Are there sub-objectives? If so, are they
necessary to win the game or do they just expand the gameplay experience?

## Game Mechanics 🗺️

Game mechanics
: refer to how the player controls the game and the rules regarding player movement, environment allowances, and general
game rules.

Mechanics include the following:

* **Game space:** refers to where the game is set.
* **Game state:** refers to the score, health, or current level of the player or other similar variables.
* **Actions:** refers to the options accessible to the player to change the game state (e.g., character movement).
* **Skills:** refers to the skill set the player must possess to complete the game.
* **Elements of chance:** refers to the randomness or uncertainty in a game (e.g., enemy actions, dice roll).

![A screenshot of Super Mario Bros.](https://static-assets.codecademy.com/Courses/intro-to-game-dev/design/mechanics/super-mario.png)

In the game _Super Mario Bros._, Mario jumps to retrieve a mushroom that can make him big. This allows him to be hit
twice before losing a life. Besides that, its game mechanics include the following:

* **Space:** The game is described by a fast-paced side-scroller that includes platforms, enemies, and power-ups.
* **State:** The stats at the top include the character the player is controlling, the score, the number of coins, the
  current level, and the time left to complete the level.
* **Actions:** Mario can walk, run, jump, and click
* **Skills:** The player must combine the actions mentioned to complete the levels, collect coins, or get points more
  efficiently.
* **Randomness:** Enemies can either follow patterns or move unpredictably (e.g., Lakitu throws spiked shell enemies at
  Mario from a cloud throughout the level).

<note>Match the reward and penalty parameters with the desired player experience. Either praise them for doing well or encourage them for doing poorly.</note>

### Exercise: Game Mechanics

Use the attached controls to change aspects of the game mechanics. Find the best combination to make the game more
satisfying:

* Use "**Show Timer**" to toggle the visibility of the countdown timer, which affects the game state.
* Use "**Codey Binary Blast**" to toggle whether Codey can shoot projectiles to defeat bugs, which affects the game
  actions.
* Use "**Codey Move Speed**" to change how fast Codey moves, which affects both the game actions and skills.

## Game Story 📖

With certain game types, you may have to create a storyline to help players connect with your game more. Meanwhile, the
mobile game Flappy Bird may only require the player to avoid a series of pipes.

When designing a game, you should match its storyline with the game objectives. Whereas one motivates the player to
continue, the other leads them to the end goal, which they have been working to achieve throughout the game.

In the Pokémon example before, while collecting Pokémon gets users to play the game, the story allows them to connect
with it more deeply. Moreover, winning a battle encourages them, while catching a rare Pokémon may satisfy them.

Remember to match the storyline with the intended play experience.

### Exercise: Game Story

Study the storylines of the following games:

* **Final Fantasy XV:** Along with his friends, Prince Noctis must use the powers of the Lucian Kigns to defeat Niflheim
  and reclaim his kingdom.
* **Assassin's Creed:** Assassins struggle against the Templars for peace and free will, while the latter fight for
  peace via order and control.
* **Batman: Arkham City:** To free himself, Batman must uncover the scheme Batman behind Arkham City's prison's warden
  Hugo Strange.
* **Starcraft:** Human Terrans, Psionic Protoss, and Insectoid Zergs fight each other to dominate a remote galactic
  region.

## Game Platform

Game platform
: the physical hardware on which the player plays the game.

Consider the platform on which the user plays your game depending on your needs:

### Personal computer (PC) 🖥️

* It can include the latest hardware to play resource-intensive games.
* While there exists an industry that configures computers for gameplay, not all computers can play all games, such as
  those containing older hardware configurations.

### Console 🕹️

* While porting a game to a console allows you to take advantage of its powerful hardware (e.g., Nintendo Switch,
  PlayStation 5, Xbox), you must use the relevant developer tools for each console, which can be difficult for
  independent game designers.

### Mobile 📱

* Porting to a mobile platform allows you to reach more people who can play your game on the go or at home. However,
  since phone hardware is weaker than computers or gaming consoles, consider how much it can limit your ability to
  provide a rich user experience.

### Exercise: Game Platform

Study the pros and cons of each game platform below:

<table style="both">
<tr><td>Platform</td><td>Pros</td><td>Cons</td></tr>
<tr>
<td>Computer</td>
<td>

* common and readily available
* can be relatively cheap
* replaceable and upgradable hardware

</td>
<td>

* expensive high-end hardware
* modern games require expensive hardware
* cannot be used on-the-go

</td>
</tr>
<tr>
<td>Console</td>
<td>

* specifically designed for gaming
* cheaper high-quality hardware
* supports multiplayer

</td>
<td>

* does not include screen or monitor
* available only in certain regions
* cannot be used on-the-go

</td>
</tr>
<tr>
<td>Mobile</td>
<td>

* very common and readily available
* playable anywhere and on-the-go
* small and versatile

</td>
<td>

* no optimized hardware for gaming
* cannot handle high-end games
* rarer multiplayer games

</td>
</tr>
</table>

## Game Controls

Game controls
: the input in a video game.

Consider the most appropriate player controls depending on your needs. Most video game input types include the
following:

* **game controller** 🎮 (e.g., gamepad or joystick)
* **keyboard and mouse** ⌨️🖱️
* **touchscreen** 📱
* **real-world interface** 🎲 (e.g., steering wheel)

Consider the characteristics of each input type:

<table style="both">
<tr>
<td>Controller Type</td><td>Description</td>
</tr>
<tr>
<td>Game Controller</td>
<td>

* most widely used for all consoles
* cheap
* intuitive and specifically designed for console games

</td>
</tr>
<tr>
<td>Keyboard and Mouse</td>
<td>

* most common for PC games
* ergonomically designed for gaming (but expensive)
* can provide extra keys

</td>
</tr>
<tr>
<td>Touchscreen</td>
<td>

* standard for mobile games
* convenient, lighter, and lesser on equipment
* customizable on-screen controls
* may not suit classic games intended for game controllers

</td>
</tr>
<tr>
<td>Real-World Interface</td>
<td>

* custom-built controller
* expensive
* designed to mimic real-world vehicle controls (e.g., flight, racing)

</td>
</tr>
</table>

As virtual reality and augmented reality become more common, developers will design more games to suit their innovative
controls.

## Review

You have learned the following:

1. Consider the **game type**.
2. Consider the intended **player experience**, which is central to the design process.
3. Define the **goals** of your game via objectives and sub-objectives.
4. Make the **storyline** that illustrates your game's objectives.
5. Consider the intended **platform**.
6. Consider **player controls** vis-à-vis the chosen platform.

### Challenge

![A screenshot of Untitled Goose Game](https://static-assets.codecademy.com/Courses/intro-to-game-dev/design/review/goose.png)

The popular _Untitled Goose Game_ requires completing tasks while avoiding most people.

Do you think the developers started this idea by wanting an adventure game starring a goose, wanting to control a goose,
or wanting to build an adventure game?

What do you think drives the popularity of the game? Is it how rare it is to control a goose? Is it the story behind the
main gameplay or how simple the mechanics are?

Game developers focus on game element design before coding or creating the assets. Doing so keeps the game development
process organized.

<seealso>
<category ref="introduction-and-game-design">
<a href="https://www.codecademy.com/resources/docs/general/software-development-life-cycle">General | Software Development Life Cycle | Codecademy</a>
<a href="https://gamedevbeginner.com/how-to-write-a-game-design-document-with-examples/">How to write a game design document (with examples)</a>
<a href="https://en.wikipedia.org/wiki/Game_design_document">Game design document - Wikipedia</a>
<a href="https://www.geeksforgeeks.org/game-design/">Game Design - GeeksforGeeks</a>
</category>
</seealso>
