# Game Assets: Lesson

<show-structure for="chapter,procedure" depth="2"/>

## Introduction to Assets

Asset
: In game development, it is an art component contributing to the game's look, feel, and sound (e.g., characters, visual
environment and scenes, sound effects, soundtracks).

This lesson discusses the following:

* What assets are and how they have transformed over the years
* How to conceptualize and model objects for game integration.
* How to create character assets
* How to create environment or scene level objects
* How to create and use sound effects
* How to create and use musical compositions or game soundtrack

### Exercise: Introduction to Assets

Study the following character assets from popular video games:

<table>
<tr><td>Game</td><td>Image</td></tr>
<tr>
<td>Pac Man. Namco, 1980.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/intro/assets/pm.gif" alt="Pac Man" /></td>
</tr>
<tr>
<td>Mortal Kombat XI, Warner Bros. Interactive Entertainment, 2019</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/intro/assets/mk.gif" alt="Moral Kombat XI" /></td>
</tr>
<tr>
<td>The Sims 4. Electronic Arts, 2014</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/intro/assets/sm.gif" alt="The Sims 4" /></td>
</tr>
</table>

## History of Game Assets

Assets play a crucial role in video games by shaping the game's look and feel and keeping players engaged in the
storyline and gameplay.

Examples of game assets include characters, level environments, interactable and non-interactable objects, sound
effects, and music.

Over the past 30 years, technological advances have allowed for more realistic characters, environments, and engaging
soundtracks. As asset quality and detail have improved, players can easily distinguish games by their unique characters,
colors, and recognizable sounds, such as those from Pac-Man or Super Mario.

Game assets have evolved from 2D to 3D as developers allocate more time and budget to their creation. High-quality
assets not only immerse players but also serve as vital marketing tools for promoting video games.

### Exercise: History of Game Assets

Study the difference between the old and newer Lara Croft character.

<table>
<tr><td>1996</td><td>2018</td></tr>
<tr>
<td>

![Tomb Raider. Eidos Entertainment (1996)](https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/history/assets/lc1.png)
</td>
<td>

![Shadow of the Tomb Raider. Square Enix (2018)](https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/history/assets/lc4.png)
</td>
</tr>
</table>

## Asset Conceptualizing and Modeling

To bring a video game to life, designers must model and refine the character and object designs. The process of
preparing a game asset for incorporation involves the following steps:

<procedure>
<step><control>Conceptualizing:</control> This initial phase produces detailed descriptions and illustrations of the object or character, often requiring multiple rounds of revisions on rough sketches.</step>
<step><control>Sculpting:</control> This stage converts concept materials into 3D models using software like Blender or Spine, creating either low or high-detail models.</step>
<step><control>Texturing:</control> This stage applies visual effects by wrapping 2D images around the modeled asset, enhancing realism and detail.</step>
<step><control>UV Mapping:</control> This process wraps the created texture around the newly modeled 3D object.</step>
<step><control>Baking:</control> This process transfers 3D geometric details from one model to another and is commonly used to convert high-detail models into low-detail versions.</step>
<step><control>Lighting:</control> Adding lighting enhances depth perception and can involve shadowing or directed lights to illuminate the scene.</step>
</procedure>

## Creating Character Assets

After the artist designs the characters, we sketch their silhouettes, which is crucial in the character conception
process, conveying key features such as:

* **Physical features:** Elements like skin, hair, and beauty marks enhance the natural appearance.
* **Subtle features:** Their build, pose, and facial expressions help players choose characters and understand their
  intentions in the storyline.

In games where players must quickly decide if a character is a friend or foe, assets significantly influence those
choices. Clothing, poses, and facial expressions guide their decisions.

### Exercise: Creating Character Assets

Study how the physical appearance of Aloy from Horizon Zero Dawn can help create a character that influences and
supports the storyline of a game.

![Horizon Zero Dawn. Guerilla Games, 2017](https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/character/hzd.png)

## Creating Environment Assets

Game level
: the space or environment where the player performs actions to achieve a goal.

Environment assets include all details at a level that advances the storyline and immerses the player. These assets
encompass both foreground and background components.

**Foreground objects** interact with the player, while **background objects** primarily enhance the environment's
appearance.

Designers first sketch environment assets by researching and collecting references for all scene components.

Environment design varies significantly between mobile devices and consoles. Mobile screens require smaller sizes and
fewer components, and limited hardware capabilities may reduce asset detail.

![Jetpack Joyride 2 screenshot](https://static-assets.codecademy.com/Courses/intro-to-game-dev/assets/environment/jetpack.png)

This screenshot of Jetpack Joyride 2 showcases layers of assets. Foreground assets include the large boss mechatronic
and frightened lab workers on the floor.

Background assets effectively create depth by layering various stage elements, from the floor and ceiling to distant
rock formations.

Creating a scene involves multiple assets that work together seamlessly.

### Exercise: Creating Environment Assets

In Codey's Adventure, use the following controls to customize the look of the game:

* The "**Background Color**" control allows you to choose the background color.
* The "**Platform Material**" dropdown lets you change the platform's texture.
* The "**Floor Material**" dropdown lets you change the floor's texture.

## Creating Sound Effect Assets

Sound effects are essential in video games, enhancing player engagement and evoking specific moods based on the scene.
They may serve the following purposes:

* **Convey plot or environment information:** For example, they help indicate an abandoned environment.
* **Provide feedback on player actions:** A chime sound effect can play when players collect items, offering positive
  reinforcement for their actions.
* **Create emotional impact:** A loud bang can alert players to potential threats, invoking fear or excitement to drive
  gameplay.

Types of sound effects in a game include:

* **Narration:** Dialogues between characters or narrated text that provide additional information, such as a character
  saying, "It's locked!" when trying to open a door.
* **Ambient sounds:** Sounds may refer to background noises that set the scene, like howling wind or dripping water.
* **Sound effects:** Attention-grabbing sounds, such as bangs, crashes, or explosions.
* **Foley sound effects:** Sounds that match in-game actions, like a "thump" when a player bumps into a table or glass
  breaking when entering through a window.

## Creating Musical Composition Assets

Thematic and incidental music is crucial in video games, evoking a wide range of emotions as players navigate the
storyline. Music also establishes the timeline and foreshadows upcoming events.

Adaptive or interactive music is common in video games, responding to specific events through changes in tune, volume,
and rhythm.

One challenge in creating game music is that players complete scenes, tasks, or levels at different speeds.
Complementary music blocks can help address this issue.

A well-developed composition seamlessly loops music blocks for players who need more time, preventing awkward silence
during gameplay.

Several types of musical blocks can vary in length and connect at different points:

<table style="both">
<tr><td>Name</td><td>Description</td><td>Example</td></tr>
<tr>
<td>Intro</td>
<td>sets the mood for the game, level, or scene.</td><td>when you start a new game, when the title or opening credits show, or when the characters are introduced.</td></tr>
<tr>
<td>Loop</td>
<td>repeats a section of music until an event occurs, such as a character dying or finding an object.</td><td>the player navigates through the level</td></tr>
<tr>
<td>Transitional</td>
<td>connects scenes seamlessly, helping the game flow from interactive play to cutscenes.</td><td>task completion triggers a non-playable cutscene</td></tr>
<tr>
<td>Stinger</td>
<td>marks a momentous event, typically lasting a few seconds, like intense music when a character loses grip</td><td>player slips off a ledge</td></tr>
<tr>
<td>Tag</td>
<td>signals at the end of a scene or level, indicating to players that they have completed it.</td><td>player defeats all zombies in a room, transitioning from high-intensity loop music to a normal-paced one</td></tr>
</table>

All sound clips and tracks should complement each other to create a cohesive soundtrack.

## Review

You have learned the following:

* The importance of **game asset creation**
* The **history** and progression of game assets
* The process for **creating and modeling assets**
* The visual asset creation process for **characters** and **environments**
* The music asset creation process for **sound effects** and **soundtrack compositions**
* How we use these assets in games and influence player gameplay or player emotional response
