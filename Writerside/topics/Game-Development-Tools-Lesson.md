# Game Development Tools: Lesson

## Introduction

Without tools, modeling characters and coding mechanics would be tedious, making simple projects take months or years to
prototype, with only a few experts able to do so.

Just as a mechanic needs a screwdriver and a painter needs an easel, every role in game development requires specific
tools. Sound designers use audio production software to create and edit audio assets, programmers utilize various
languages and compilers for logic, and animators employ modeling software to animate 2D or 3D characters. Game
development offers software that provides all the necessary tools to build a game.

The video game industry's recent boom has led to the availability of many tools, which have also contributed to this
growth. These tools enhance productivity in every aspect of game development while reducing production time and costs.
They enable the creation of expansive games and empower indie developers to build worlds, tell immersive stories, and
connect players globally.

### Exercise: Introduction

Study what you think the developers of Red Dead Redemption 2 used to make the game.

![Red Dead Redemption 2. Rockstar Games (2018)](https://static-assets.codecademy.com/Courses/intro-to-game-dev/tools/intro/rdr2.png)

## Programming Languages

### C++ {id="c_1"}

C++ is the most popular programming language for game development, known for its unmatched performance and proximity to
hardware, making it the standard for consoles and PCs. Although its low-level components can make it complex for
developers to learn, those seeking flexibility and control may find it worthwhile. C++’s object-oriented design enables
maintainable and reusable code. However, developers may choose other languages to prioritize coding speed over
performance.

### C#

C# is a simple, modern object-oriented language created by Microsoft. It is ideal for building games on Windows and
Xbox, and Microsoft has developed tools and frameworks to make it cross-platform. C# can also serve as a backend
language for server communication.

### Java

Java is a cross-platform, object-oriented language that runs on a virtual machine, facilitating easier scaling and
distribution of games. Its open-source resources and support for multithreading and socket programming make it popular
for indie, mobile, and multiplayer games.

### HTML5 and JavaScript

HTML5 is the core technology for games running on web browsers and mobile platforms like iOS and Android. It combines
HTML, CSS, and JavaScript to create interactive online games, allowing virtually anyone to play games built with HTML5
in a web browser.

### Lua

Lua is a high-level, lightweight, cross-platform language that runs on virtual machines. Its highly embeddable nature
makes it convenient for game developers, allowing easy integration into other applications. Roblox exemplifies the use
of Lua for creating games with a game engine, which we will explore in the next exercise.

### Exercise: Programming Languages

Review the programming languages introduced:

* C++
    * A standard for game development
    * Best performance
    * Close proximity to hardware
    * Challenging but provides most flexibility and control
* C#
    * Designed by Microsoft
    * Best for Windows and Xbox
    * Tools make it cross-platform
* Java
    * Object-oriented language
    * Runs on a virtual machine
    * Makes games easy to scale and distribute
* HTLML - JavaScript
    * Run within web browsers
    * Create interactive online games
    * Most accessible
* Lua
    * Easy to integrate into other languages
    * Lightweight
    * Runs on a virtual machine

## What is a Game Engine?

Game engines
: also game frameworks, are development environments that simplify, optimize, and accelerate game development cycles.

They include a diverse set of tools that provide essential core functionality, such as:

* **Rendering:** Generating images from 2D or 3D models.
* **Physics:** Pre-configured settings to simulate real-world behavior and collision detection.
* **Lighting:** Managing various lighting effects, including diffusion, scattering, and ray tracing.
* **AI:** Creating behaviors for game elements.
* **Sound:** Producing sound effects.
* **Asset Store:** Downloading pre-built (and sometimes free) game assets.

Game engines provide a foundation for developers to build upon, significantly reducing production time and costs.
Developers can use these tools to focus their time, energy, and resources on game mechanics and storytelling instead of
coding physics or managing memory. Some engines even allow for easy porting of games between platforms.

## Game Engines

### Unity

Unity is one of the most popular game engines.

* Supports 2D and 3D games on over 25 platforms, including AR and VR.
* Uses C#.
* Easy to use with a simple interface.
* Features an asset store with numerous free assets.
* According to the [2021 Gaming Report](https://create.unity.com/2021-game-report) by Unity:
    * Used to create 90% of Samsung Gear and 53% of Oculus Rift VR games.
    * Chosen by 61% of game developers.
* Powers many mobile games, including Pokémon Go and Temple Run.

### Unreal Engine

Unreal Engine, developed by Epic Games (creator of "Fortnite"), powers many popular games.

* Provides extensive tools for developers to realize their creative vision.
* Features high-end graphics with advanced rendering and lighting engines.
* Uses C++ by default.
    * Supports other languages like Python.
    * Offers a blueprint visual scripting system for adding logic and interactivity without coding.
* Includes a marketplace with free assets.

However, its powerful tools may not suit small teams or solo developers, and it is better for 3D than 2D games.

### GoDot

GoDot has gained popularity for its simplicity and free commercial license.

* Supports both 2D and 3D game development.
* Uses GDScript by default, a Python-like scripting language
    * Supports C++, C#, and others.
* Features a unique node and scene organization for easy game design.

Other notable game engines
include [CryEngine](https://www.cryengine.com/), [GameMaker Studio 2](https://gamemaker.io/en/gamemaker),
and [PyGame](https://www.pygame.org/wiki/about). Many are open-source and continuously improved by the community. While
most are free to start, some require a license for commercial distribution. For example, Epic Games charges a 5% royalty
fee after a game earns $1 million in gross revenue. Research features, tools, pricing, and licensing options before
starting development.

### Exercise: Game Engines

Review and compare the game engines mentioned in the table below:

![Game engine comparison table](https://static-assets.codecademy.com/Courses/intro-to-game-dev/tools/game-engines/engine-chart.png)

## Game Engines for the Web

### HTML5

HTML5 refers to a collection of modern web technologies, including HTML, CSS, and JavaScript, along with APIs like WebGL
and WebSockets that enhance web game development. HTML5 games are cross-platform, functioning on any modern
device. [Numerous game engines support HTML5](https://html5gameengine.com/); here are some of the most popular.

### Phaser

[Phaser](https://phaser.io/) is a fast, free, open-source 2D HTML5 game engine that uses WebGL and Canvas rendering for
web browsers across desktop and mobile. Third-party tools and plugins allow developers to compile games as native iOS,
Android, and desktop applications.

### GDevelop

[GDevelop](https://gdevelop.io/) is a free, open-source HTML5 game engine for building 2D games. Its key features
include visual programming and one-click cross-platform distribution. It supports JavaScript for extending functionality
and can export standalone games to various platforms, including Windows, Linux, and mobile.

### Construct 3

[Construct 3](https://www.construct.net/) is an HTML5 game engine for creating 2D and 3D games. It offers visual
programming, JavaScript support, and efficient distribution to multiple platforms. However, it is not entirely free.

### Honorable Mentions

Choosing the best HTML5 game engines depends on the specific features required. Notable mentions include:

* [**ImpactJS:**](https://impactjs.com/) A free, high-quality 2D and 2.5D game engine.
* [**PlayCanvas:**](https://playcanvas.com/) A 3D HTML5 game engine with cloud-based tools.
* [**PixiJS:**](https://pixijs.com/) A fast 2D rendering engine for creating rich animations, graphics, and games, used
  by many engines, including Phaser, GDevelop, and ImpactJS.
* [**Three.js:**](https://threejs.org/) The most popular JavaScript framework for creating and animating 3D graphics in
  the browser.

### Exercise: Game Engines for the Web

Review and compare the web engines mentioned in the table below:

![Web engine comparison table](https://static-assets.codecademy.com/Courses/intro-to-game-dev/tools/web-engines/web-engine-chart.png)

## Asset Tools

### Blender

[Blender](https://www.blender.org/) is a free, open-source 3D creation software that handles all aspects of the 3D
pipeline, including modeling, rigging, animation, simulation, and rendering. It enables the creation of visual effects,
3D models, VR applications, and animated films. Blender also features a Python API for custom scripts, allowing
integration with other tools.

### Character Creator

If you prefer not to model characters,
use [Character Creator by Reallusion](https://www.reallusion.com/character-creator/). This tool allows easy
customization of highly realistic character assets, enabling adjustments to attributes like age, weight, skin, hair, and
teeth. The marketplace offers community-made assets, including outfits, animations, and light presets, which you can
easily integrate into your game engine.

### Pro Tools

Codecademy recommends [Pro Tools](https://www.avid.com/pro-tools) for sound design and editing. It can create any audio
asset, including sound effects, ambient sounds, Foley, background music, and dialogue.

### Exercise: Asset Tools

Review the asset tools covered:

* Blender
    * 3D creation software
    * Capable of modeling, rigging, animation, simulation, and rendering
    * Offers Python API for running custom scripts
* Character Creator
    * Create customizable and highly-realistic characters
    * Tweak attributes like age, weight, skin, hair, teeth
    * Offers market with existing assets
* Pro Tools
    * Design and edit sound effects
    * Create audio assets like ambient sound, foley, background music, and dialogue

## Distributing and Publishing

### PC

#### Itch.io

[Itch.io](https://itch.io/) is an indie game marketplace that charges no application fees, requires no content review or
waiting periods for publishing, and does not contain DRM or exclusivity clauses.

#### Steam

[Steam](https://store.steampowered.com/) is the most popular PC video game storefront, offering features like game save
uploads, automatic updates, user-created content support, and social networking. However, publishing on Steam comes with
additional policies and requirements.

Other digital storefronts for PC games include
the [Epic Games Store](https://store.epicgames.com/en-US/publish), [Humble](https://www.humblegames.com/submit-a-game/),
and [GOG](https://www.gog.com/indie).

### Console

Following the success of indie games like Minecraft, console manufacturers such as Sony, Microsoft, and Nintendo have
established indie developer programs:

* Sony's [PlayStation Partners](https://partners.playstation.net/)
* Microsoft's [ID@Xbox](https://www.xbox.com/en-US/developers/id)
* Nintendo's [Developer Portal](https://developer.nintendo.com/)

### Mobile

To share games for Android or iOS, use [Google Play](https://play.google.com/console/about/) or
Apple's [App Store](https://developer.apple.com/app-store/submitting/).

### Web

Web games can run on any modern device with a browser, provided developers optimize them for various screen sizes and
input types. Distributing games on the web allows for easy sharing via hyperlinks on social media to generate interest.
For monetization, consider using ads or marketplaces
like [Itch.io](https://www.codecademy.com/courses/introduction-to-game-development/lessons/game-development-tools/exercises/distributing-and-publishing#Itch.io).

Regardless of the platform, review each marketplace's policies and fees before submitting a game.

## Review

We discussed the importance of selecting the proper programming language and tool for your project. Embrace your freedom
of choice and conduct thorough research before committing.

Remember, no game engine or platform is inherently better than another, and popularity holds little significance. The
most crucial aspect of video game development is your passion for creating games—building stunning worlds, inventing
unique characters and immersive stories, developing innovative gameplay mechanics, and sharing your creations with the
world.

### Challenge

Returning to Red Dead Redemption 2 with another screenshot, remember the diverse experience this game offers players is
a fruit of the collaboration of many teams and the tools they use to create such expansive opportunities and
experiences.

![Red Dead Redemption 2. Rockstar Games (2018)](https://static-assets.codecademy.com/Courses/intro-to-game-dev/tools/review/rdr2.png)
