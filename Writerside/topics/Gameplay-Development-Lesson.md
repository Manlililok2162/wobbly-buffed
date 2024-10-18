# Gameplay Development: Lesson

<show-structure for="chapter,procedure" depth="2"/>

## Introduction

After designing the game, we ought to make fundamental decisions to realize this vision. But before that, you must learn
the core concepts of what makes a video game.

This lesson discusses the following important aspects of a video game:

* gameplay
* mechanics
* AI
* user experience and interface
* customization

### Exercise: Introduction

![Witcher 3 screenshot](https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/intro/witcher3.jpeg)

Study the screenshot above and identify the existing video game development components.

## Gameplay

Gameplay
: encompasses the entire gameplay experience including:
: * the player-game relationship
: * the game objectives or challenges and how the player overcomes them
: * the plot and the role of the player in it

Gameplay also encompasses how much a game adheres to or departs from its genre's formula. For instance, while Minecraft,
Call of Duty, Portal, and SUPERHOT classify as first-person shooters, each offers distinct gameplay. Thus, we can
categorize gameplay into the following types:

### Cooperative

A co-op game lets players cooperate against one or more non-player character (NPC) opponents.

### Asymmetric

It involves multiplayer games where different groups play in the same match with distinct mechanics, such as zombie or
survival games where one team survives against monsters controlled by other players.

### Nonlinear

It allows players to choose their path and actions, creating a free-form branching journey typical of progressive
open-world games and massively multiplayer online role-playing games (MMORPGs).

### Emergent

It features mechanics that evolve based on player actions, requiring simple decisions that lead to complex outcomes,
with narratives changing according to player choices.

### Exercise: Gameplay

Study the different game types in the table below:

<table style="both">
<tr><td>Gameplay Type</td><td>Description</td></tr>
<tr><td>Cooperative</td>
<td>

* Players cooperate as teammates.
* They fight against one or more NPC characters.

</td>
</tr>
<tr><td>Asymmetric</td>
<td>

* Two or more groups exist in a multiplayer game.
* Gameplay mechanics differ with each group.
* Example: survival games where players control the monsters.

</td>
</tr>
<tr><td>Nonlinear</td>
<td>

* Players choose their action or path.
* Journey branches out.
* Example: open-world games or MMORPGs.

</td>
</tr>
<tr><td>Emergent</td>
<td>

* Game mechanics depend on player actions.
* Simple decisions lead to complex outcomes.
* Example: narrative-driven games with multiple endings.

</td>
</tr>
</table>

## Mechanics

Mechanics
: how the game works for its players
: rules guiding player actions and how the game responds
: describes character abilities

Gameplay
: how the players experience the game

In a way, **mechanics** act in _engineering_, while **gameplay** acts in _design_.

Fundamental game mechanics may include the following:

* **Movement:** It varies significantly across game types: 3D games offer six degrees of freedom, while platformers
  limit movement to left and right. Other mechanics include jumping, swimming, and sprinting.
* **Energy Points:** They include health, shield/armor, magic, and action points.
* **Character Actions**: They encompass shooting, crafting, attacking, and taunting.
* **Resource Management:** It involves handling money, land, natural resources, and mechanics like health regeneration
  and player death.

### Exercise: Mechanics

![Final Fantasy VII battle scene](https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/mechanics/ff7a.png)

Study the battle scene from Final Fantasy VII following the number markers:

1. As a turn-based game, this text reference lists all controllable player characters
2. All possible actions with the currently chosen player character.
3. Energy points: health points, mana points, limit, and time.
4. Visual reference of all controllable player characters.

## Artificial Intelligence (AI)

AI encompasses self-driving cars, recommendation systems, voice assistants.

Artificial intelligence (AI)
: refers to the computer system's ability to perform complex tasks (e.g., driving cars, translating languages, folding
laundry, playing video games).

Video games commonly use AI to control NPC behavior to increase game responsiveness and adaptiveness.

AI also powers decision-making of NPCs, resulting in more interactive and immersive gaming experiences.

<procedure title="3-Step Cycle">
<p>Basic video game AI follows this simple three-step cycle:</p>
<step><control>Sense:</control> observe the surroundings</step>
<step><control>Think:</control> make a decision</step>
<step><control>Act:</control> carry out the decision</step>
</procedure>

Examples:

* Platformer-type enemies wait until the player gets close enough before attacking.
* RPG-type enemies determine and attack the weakest player.
* **Red Dead Redemption 2:** NPC behavior involves living a virtual life: completing chores, working, pursuing hobbies.
* **FEAR:** Enemies adapt to the player's play style in this horror first-person shooter.
* **Minecraft:** Procedural level generation increases replayability and reduces predictability.

With that, AI enables complex behaviors automatically to save time and cut costs.

### Exercise: Artificial Intelligence (AI)

In Codey's Adventure, change the enemy behavior using the following controls:

* The "**Enemy Walk Speed**" slider controls how fast the enemy moves when it has not detected the player character.
* The "**Enemy Sprint Speed**" slider controls how fast the enemy moves when it has detected the player character.
* The "**Show Sense Radius**" checkbox toggles the visibility of the enemy's red sense radius.
* The "**Enemy Sense Radius**" slider controls the size of the sense radius of all enemies.
* The "**Enemy Idle Behavior**" dropdown selects what the enemies do when they have not detected Codey.
* The "**Enemy Sense Behavior**" dropdown selects what the enemies do when they have detected Codey.

## User Experience (UX)

User experience (UX)
: refers to everything with how a user interacts with a product.
: Its goal is to improve usability and ease user-game interaction to increase player satisfaction and loyalty.

UX encompasses human perception, attention, and memory. The director of UX at Epic Games, Celia Hodent, lists **seven
usability heuristics** game designers should follow:

1. **Signs and feedback:** signs refer to info that alerts players of possible or future scenarios, while feedback (
   e.g., visual, audio, haptic) refers to responses to actions.
2. **Clarity:** Make visible symbols and text legible and perceived as intended.
3. **Form follows function:** The object form should give info about its function.
4. **Consistency:** Make controls, signs, feedback, and UI as consistent as possible.
5. **Minimum workload:** Reduce the memory (RAM) burden.
6. **Error prevention or recovery:** Help players prevent or quickly recover from errors.
7. **Flexibility:** Let players customize their gaming experience.

While some players can tolerate poor graphics or stories, poor UX frustrates everyone leading to uninstalls due to
unintuitive interfaces and improper responsive interactions.

Good UX practices include the following in the table below:

<table>
<tr><td>Image</td><td>Description</td></tr>
<tr>
<td><control>Color Indicators:</control> These signal different scenarios, with red indicating immediate attention and green representing player health.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/mc.png" alt="Mobs turn red when hit in Minecraft" /></td>
</tr>
<tr>
<td><control>Subtitles:</control> In text-based games, these are color-coded by character, with certain words animated to convey emotion.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/kz.png" alt="Katana Zero released in 2019 by Devolver Digital" /></td>
</tr>
<tr>
<td><control>Combo Indicators:</control> Fighting games feature these. Also, enemies often have indicators above their heads when attacking or alerted.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/bao.png" alt="Batman: Arkham Origin released in 2013 byWarner Bros. Interactive Entertainment" /></td>
</tr>
</table>

### Exercise: User Experience (UX)

Study the following UX examples in the table below:

<table>
<tr><td>Description</td><td>Image</td></tr>
<tr>
<td><control>Rise of the Tomb Raider. Square Enix, 2015.</control> The game immerses the player in the environment as they level up their skills.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/assets/tr.png" alt="screenshot" /></td>
</tr>
<tr>
<td><control>Dead Space. Electronic Arts, 2008.</control> This horror action game does not pause when players access their inventory. The game also displays their health on the character's back.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/assets/ds.png" alt="screenshot" /></td>
</tr>
<tr>
<td><control>Fortnite. Epic Games, 2017.</control> The game uses several usability heuristics, including minimum workload, by consistently displaying each gun's ammo type and the player's resource count.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/assets/fn.png" alt="screenshot" /></td>
</tr>
<tr>
<td><control>Metal Gear Solid: Peace Walker. Konami, 2010.</control> When an enemy detects the player, the game displays an exclamation mark above the enemy and plays a warning sound.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/assets/mgs.png" alt="screenshot" /></td>
</tr>
<tr>
<td><control>Overwatch. Blizzard Entertainment, 2016.</control> The game displays the round status, points, kill feed, and healing or damage vignette on the screen.</td>
<td><img src="https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ux/assets/ow.png" alt="screenshot" /></td>
</tr>
</table>

## User Interface (UI)

User interface (UI)
: bridges human-computer interaction

While UX refers to what the user takes away from the whole experience, UI refers to all elements enabling the user to
interact with the product. It includes car dashboards and website pages wherein the best ones are those users do not
notice.

Heads-up display (HUD)
: a common game UI element showing relevant info, such as health, magic, ammo, weapon, mini-map, and compass.

![Mass Effect, Electronic Arts (2007)](https://i.pinimg.com/originals/a8/05/2d/a8052deb0b3b147d64cf78bfe5749fe2.jpg)

The HUD varies by game, with some developers choosing to disguise or hide it for realism. It also exemplifies the
minimum workload usability heuristic by reducing the player's memory load.

Other game UI examples include the following:

* **Main Menu:** This serves as the starting point for any great experience, requiring a polished and immersive design
  to create a strong first impression.
* **Tutorial:** If our game includes unique mechanics or complex rules, we must design a hands-on tutorial.
* **Map:** A game world should have a clear and detailed, especially in large environments, to encourage exploration
  without frustrating players who might get lost.

There is no single correct approach to UI design in video games, making it one of the most challenging aspects of game
development due to its subjective nature. Game developers should invest time in creating effective UI and UX to ensure a
comfortable user gaming experience.

To explore more about UI/UX and usability heuristics, consider taking
Codecademy's "[Intro to UI/UX](https://www.codecademy.com/learn/intro-to-ui-ux)" course.

### Exercise: User Interface (UI)

Study the marked areas in this screenshot of Apex Legends:

1. Minimap
2. Teammates and their health
3. Compass
4. Kill feed and remaining players
5. Skills and respective buttons to use them
6. Current gun and ammo
7. Low health is represented by the pixelated reddish border

![Apex Legends screenshot](https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/ui/al.png)

## Flexibility

Customization
: gives players freedom to choose how they want to play.

You can provide flexibility by adding the following options:

* **Game Settings:** Allow players to adjust settings like resolution, language, and sound levels, and edit UI colors
  and HUD transparency.
* **Gameplay Tweaks:** Let players customize characters and weapons, change playstyles at any time, and adjust AI
  behavior by modifying difficulty levels.
* **Quality of Life:** Improve the gaming experience by adding features like weapon loadouts, fast travel, skippable
  cutscenes, and quick restarts.
* **Accessibility:** Allow players with disabilities to customize the UI and game controls for maximum comfort.

Allowing users to play however they want can be both good and bad. Too many options can overwhelm players, especially
newcomers, and gameplay-affecting customization can disrupt balance in multiplayer games. Always ensure added
customization does not significantly alter the intended gaming experience or detract from the story and emotions the
game intends to convey.

The best customization options minimally impact the game's design and integrate seamlessly into the world or story. For
example, you can easily weave fast travel into the narrative.

While you can add customization, you should monitor player feedback since players often overlook flexibility unless it
is lacking.

### Exercise: Flexibility

Study the settings menu screenshot from Forza Horizon 5, which offers numerous options to adjust Drivatar difficulty (
AI-controller cars). Features like manual shifting increase difficulty and the bonus currency awarded at the end of each
race. Also, note the configurable options for accessibility, HUD, and language selection.

![Forza Horizon 5 menu screenshot](https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/flexibility/forza.png)

## Review

You have learned the following:

* **Gameplay:** It consists of game mechanics and defines what players take away from their gaming experience.
* **Game Mechanics:** These are the rules that guide player actions and the game's responses.
* **AI in Games:** This enhances interactivity and immersion, enabling functions like pathfinding and NPC behaviors.
* **Advanced AI use:** As the future of gaming, with unexplored capabilities, it can make games smarter and more
  realistic while saving time and money.
* **UX and UI:** UX encompasses all aspects of user-game interaction, while UI includes the elements that facilitate
  that interaction.
* **Usability Heuristics:** Following usability heuristics and guidelines, such as Diegesis theory, helps us design
  effective UX and UI, increasing player engagement.
* **Customization:** Allowing players to customize their gaming experience is not essential but adds value to video
  games.

### Challenge

Study the game development aspects of this screenshot of The Witcher 3.

* **Gameplay:** Extracting the gameplay type from a single screenshot is challenging. As an open-world action
  role-playing game (ARPG), The Witcher 3 features nonlinear gameplay, supported by a mini-map indicating a vast game
  world.
* **Mechanics:** The HUD displays basic fighting mechanics like attacks, dodging, and spellcasting. As a 3D game, it
  likely offers freedom of movement in six degrees, including swimming. The HUD also shows energy points like health,
  mana, and armor, suggesting resource management and crafting due to the presence of potions and sword types.
* **AI:** The appearance of Drowner enemies charging toward the player indicates the game likely employs different
  behavioral trees for various enemies and NPCs.
* **UI/UX:** The screenshot showcases extensive UI and UX elements. The HUD displays crucial information, including
  health, equipped weapons and potions, weather, time, location, and basic controls to ease player memory load. It also
  indicates when their armor piece is about to break and shows the name of the nearest enemy name and health above its
  head, enhancing the gaming experience.
* **Flexibility:** Although not visible in the screenshot, we can expect CD Projekt RED to offer a range of settings and
  customization options, such as fast travel, hiding tutorial controls, enabling accessibility features like colorblind
  mode, and changing the game’s language.

![Witcher 3. CD Projekt Red (2015)](https://static-assets.codecademy.com/Courses/intro-to-game-dev/gameplay/intro/witcher3.jpeg)
