# Awesome Haxe Gamedev Overview

Resources for game development on haxe

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/Dvergar/awesome-haxe-gamedev/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 Dvergar/awesome-haxe-gamedev](https://github.com/Dvergar/awesome-haxe-gamedev) · ⭐ 313 · 🏷️ Gaming

[ [Daily](/content/Dvergar/awesome-haxe-gamedev/README.md) / [Weekly](/content/Dvergar/awesome-haxe-gamedev/week/README.md) / Overview ]

---

<div align="center"><a href="https://haxe.org/"><img src="https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/haxe-logo.png" width="500"></a></div>

# Awesome Haxe Game Development [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of game development resources for **[Haxe 4](https://haxe.org/)**, a high level strictly typed programming language which is used to produce cross-platform native code.

Feel free to update it.

## Contents

*   [Game engines](#game-engines)
*   [Physics](#physics)
*   [Architecture](#architecture)
*   [Networking](#networking)
*   [Serialization and storage](#serialization-and-storage)
*   [Games](#games)
*   [Miscellaneous](#miscellaneous)
*   [Articles](#articles)
*   [Other haxe lists](#other-haxe-lists)

## Game engines

Those are Haxe 4 compatible game engines.

| Engine                                                               | Target                         | Description                                                          |
| -------------------------------------------------------------------- | ------------------------------ | -------------------------------------------------------------------- |
| [Armory (Kha) (⭐2.6k)](https://github.com/armory3d/armory)           | Web, Mobile, Desktop, Consoles | An open-source 3D game engine with full Blender integration.         |
| [Away3D (⭐158)](https://github.com/openfl/away3d)                    | Web, Mobile, Desktop           | An open source, real-time 3D engine for OpenFL.                      |
| [HaxeFlixel (OpenFL) (⭐1.6k)](https://github.com/HaxeFlixel/flixel)  | Web, Mobile, Desktop, Consoles | Free, cross-platform 2D game engine powered by OpenFL.               |
| [Haxegon (OpenFL) (⭐189)](https://github.com/haxegon/haxegon)        | Web, Mobile, Desktop, Consoles | A programming library for beginners. Powered by OpenFL and Starling. |
| [Heaps (⭐2.8k)](https://github.com/HeapsIO/heaps)                    | Web, Mobile, Desktop, Consoles | High Performance Game Framework.                                     |
| [hxdefold (⭐143)](https://github.com/hxdefold/hxdefold)              | Web, Mobile, Desktop           | Haxe/Lua externs for Defold game engine.                             |
| [OpenFL (⭐1.7k)](https://github.com/openfl/openfl)                   | Web, Mobile, Desktop, Consoles | Interactive game and app development library.                        |
| [Starling (⭐212)](https://github.com/openfl/starling)                | Web, Mobile, Desktop           | The "Cross-Platform Game Engine", a popular Stage3D framework.       |
| [Stencyl (OpenFL) (⭐169)](https://github.com/Stencyl/stencyl-engine) | Web, Mobile, Desktop           | Create Flash, HTML5, iOS, Android, and desktop games with no code.   |
| [unreal.hx (⭐404)](https://github.com/proletariatgames/unreal.hx)    | Web, Mobile, Desktop, Consoles | Haxe Integration for Unreal.                                         |

| Low-level Engine                                           | Target                        | Description                                                             |
| ---------------------------------------------------------- | ----------------------------- | ----------------------------------------------------------------------- |
| [Kha (⭐1.3k)](https://github.com/Kode/Kha)                 | Web, Mobile, Desktop, Console | Ultra-portable, high performance, open source multimedia framework.     |
| [Lime (⭐678)](https://github.com/openfl/lime)              | Web, Mobile, Desktop          | A flexible, lightweight layer for Haxe cross-platform developers.       |
| [linc\_glfw (⭐16)](https://github.com/Sunjammer/linc_glfw) | Desktop                       | GLFW binding (multi-platform library for OpenGL, OpenGL ES and Vulkan). |
| [NME (⭐455)](https://github.com/haxenme/nme)               | Web, Mobile, Desktop          | A cross-platform native backend for Haxe projects.                      |

## Physics

| Library                                                      | Description                                                                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| [echo (⭐131)](https://github.com/AustinEast/echo/)           | Simple Physics Library.                                                                                            |
| [haxebullet (⭐93)](https://github.com/armory3d/haxebullet)   | Bullet 3D Physics for Haxe.                                                                                        |
| [nape-haxe4 (⭐38)](https://github.com/HaxeFlixel/nape-haxe4) | Physics Engine (the original Haxe3 version of nape can be found [here (⭐538)](https://github.com/deltaluca/nape)). |

## Architecture

    IoC == Inversion of Control  
    EC == Entity Component  
    ECS == Entity-Component-System
    FSM == Finite State Machine
    MVC == Model View Controller

| Library                                                  | Architecture | Description                                                                    |
| -------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------ |
| [awe6 (⭐82)](https://github.com/hypersurge/awe6)         | IoC, EC      | The inverted game framework, is a development tool focused on Future Proofing. |
| [ecx (⭐51)](https://github.com/eliasku/ecx)              | ECS          | An Entity Component System framework.                                          |
| [hexMachina (⭐7)](https://github.com/DoclerLabs/hexCore) | MVC          | A powerful multi-modular MVC framework.                                        |
| [OSIS (⭐41)](https://github.com/Dvergar/OSIS)            | ECS          | Entity Component System architecture with networking support.                  |

## Networking

| Library                                                                   | Description                                    |
| ------------------------------------------------------------------------- | ---------------------------------------------- |
| [Anette (⭐36)](https://github.com/Dvergar/Anette)                         | Simple network library (no UDP).               |
| [colyseus-hx (⭐62)](https://github.com/colyseus/colyseus-hx)              | Multiplayer Game Client.                       |
| [haxe-simple-peer (js) (⭐4)](https://github.com/melonin/haxe-simple-peer) | Haxe externs for simple-peer.                  |
| [hxWebSockets (⭐61)](https://github.com/ianharrigan/hxWebSockets)         | Websockets for all Haxe platforms.             |
| Built-in                                                                  | Heaps, OpenFL (HaxeFlixel & co), Kha (Armory). |

## Serialization and storage

| Library                                                 | Description                                                 |
| ------------------------------------------------------- | ----------------------------------------------------------- |
| [Bits (⭐21)](https://github.com/RealyUniqueName/Bits)   | Binary bit flags with unlimited amount of bits.             |
| [CastleDB (⭐472)](https://github.com/ncannasse/castle)  | A structured static database easing collaboration.          |
| [hxbit (⭐137)](https://github.com/ncannasse/hxbit)      | A binary serialization and network synchronization library. |
| [PODStream (⭐20)](https://github.com/Dvergar/PODStream) | Plain Old Data serializer.                                  |

## Games

| Game                                                                        | Platform             | Engine              | Screenshot                                                                                                |
| --------------------------------------------------------------------------- | -------------------- | ------------------- | --------------------------------------------------------------------------------------------------------- |
| **RELEASED**                                                                |                      |                     |                                                                                                           |
| [Darksburg](https://store.steampowered.com/app/939100/Darksburg/)           | Desktop              | Heaps               | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/darksburg.jpg)            |
| [Dead Cells](https://dead-cells.com/)                                       | Desktop, Consoles    | Heaps               | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/dead-cells.jpg)           |
| [Defender's Quest](http://www.defendersquest.com/)                          | Desktop, Consoles    | HaxeFlixel (OpenFL) | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/defenders-quest.jpg)      |
| [Dicey Dungeons](http://diceydungeons.com/)                                 | Desktop, Consoles    | Haxegon (OpenFL)    | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/dicey-dungeons.jpg)       |
| [Evoland](http://evoland.shirogames.com/)                                   | Desktop, Mobile      | Heaps               | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/evoland.jpg)              |
| [Northgard](http://northgard.net/)                                          | Desktop              | Heaps               | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/northgard.jpg)            |
| [Papers, Please](http://papersplea.se/)                                     | Desktop, iOS, PsVita | OpenFL              | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/papers-please.jpg)        |
| [Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/) | Desktop              | HaxePunk (OpenFL)   | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/pocket-kingdom.jpg)       |
| [rymdkapsel](https://rymdkapsel.com/)                                       | Desktop, Mobile      | OpenFL              | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/rymdkapsel.jpg)           |
| [Spellbreak](https://playspellbreak.com/)                                   | PC, PS, Xbox, Switch | unreal.hx           | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/spellbreak.jpg)           |
| [The Westport Independent](http://www.doublezeroonezero.com/westport.html)  | Desktop, Mobile      | Luxe                | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/westport-independent.jpg) |
| **IN DEVELOPMENT**                                                          |                      |                     |                                                                                                           |
| [Frontier Story](https://twitter.com/jmw327)                                | Desktop              | Heaps               | ![Screenshot](https://github.com/Dvergar/awesome-haxe-gamedev/raw/master/images/frontier-story.jpg)       |

More showcase :

*   [OpenFL showcase](https://www.openfl.org/showcase)
*   [HaxeFlixel showcase](https://haxeflixel.com/showcase/)
*   [itch.io showcase](https://itch.io/games/made-with-haxe)
*   [HaxePunk showcase](https://haxepunk.com/games/)
*   [Flambe showcase (⭐741)](https://github.com/aduros/flambe/wiki/Showcase)
*   [Kha showcase (⭐1.3k)](https://github.com/Kode/Kha/wiki/Games-Built-With-Kha)

## Miscellaneous

| Type                  | Library                                                                           | Description                                                                                                                                                                             |   |
| --------------------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
| Animation             | [spine-hx (⭐52)](https://github.com/jeremyfa/spine-hx)                            | Spine runtime for Haxe automatically converted from the official Java/libgdx runtime.                                                                                                   |   |
| \_                    | HaxeFlixel                                                                        | Spine parser.                                                                                                                                                                           |   |
| \_                    | [Heaps-Spine (⭐17)](https://github.com/Beeblerox/Heaps-Spine)                     | Spine player for heaps.                                                                                                                                                                 |   |
| \_                    | [heaps-aseprite (⭐21)](https://github.com/AustinEast/heaps-aseprite)              | Load and render sprites and animations in Aseprite format.                                                                                                                              |   |
| \_                    | [openfl-aseprite (⭐15)](https://github.com/miriti/openfl-aseprite)                | Load and render sprites and animations in Aseprite format.                                                                                                                              |   |
| \_                    | [openfl-spine (⭐16)](https://github.com/rainyt/openfl-spine)                      | Render Spine animation in the OpenFL engine, rendering processing can be achieved through Sprite and Tilemap.                                                                           |   |
| \_                    | [ase (⭐13)](https://github.com/miriti/ase)                                        | .ase/.aseprite file format loader written in Haxe without external dependencies.                                                                                                        |   |
| Color manipulation    | [nxColor (⭐37)](https://github.com/oscarcs/nxColor)                               | Color manipulation library.                                                                                                                                                             |   |
| Collision             | [differ (⭐154)](https://github.com/snowkit/differ)                                | A separation axis theorem collision library.                                                                                                                                            |   |
| Data structures       | [polygonal-ds (⭐338)](https://github.com/polygonal/ds)                            | Data structures for games.                                                                                                                                                              |   |
| Editor                | [flixel-studio (⭐84)](https://github.com/Dovyski/flixel-studio)                   | In-game editor for HaxeFlixel.                                                                                                                                                          |   |
| Procedural generation | [Dungeon builder (⭐61)](https://github.com/julsam/dungeon-builder)                | A set of dungeon generation algorithm (works w/ hx4 w/ minor changes).                                                                                                                  |   |
| Localization          | [firetongue (⭐133)](https://github.com/larsiusprime/firetongue)                   | A translation/localization framework written in Haxe.                                                                                                                                   |   |
| Map parser            | [PyxelEdit Map Importer (⭐33)](https://github.com/Dvergar/PyxelEdit-Map-Importer) | Parser for maps generated by the editor PyxelEdit.                                                                                                                                      |   |
| \_                    | Heaps                                                                             | Built-in parser for Tiled.                                                                                                                                                              |   |
| \_                    | HaxeFlixel                                                                        | Parser for Tiled & Ogmo.                                                                                                                                                                |   |
| \_                    | [LEd (⭐68)](https://github.com/deepnight/led-haxe-api)                            | 2D level editor with a typed compile time loader.                                                                                                                                       |   |
| Math helpers          | [hxmath (⭐85)](https://github.com/tbrosman/hxmath)                                | A game-oriented math library for the Haxe language.                                                                                                                                     |   |
| \_                    | [haxe-glm (⭐44)](https://github.com/hamaluik/haxe-glm)                            | A toolset for using 2, 3, and 4 dimensional vectors and matrices, as well as quaternions.                                                                                               |   |
| \_                    | [hx-vector2d (⭐11)](https://github.com/markknol/hx-vector2d)                      | Worlds most complete Vector2d / Point class. With operator overloading.                                                                                                                 |   |
| Modding               | [polymod (⭐129)](https://github.com/larsiusprime/polymod)                         | An atomic modding framework for Haxe games/apps.                                                                                                                                        |   |
| Particles             | [Sparkler (⭐16)](https://github.com/RudenkoArts/sparkler)                         | Modular Particle System.                                                                                                                                                                |   |
| Monetization          | [extension-iap (⭐8)](https://github.com/charmdev/extension-iap)                   | Provides an access to in-app purchases (iOS) and in-app billing (Android) for OpenFL projects using a common API. Fork of [this (⭐68)](https://github.com/HaxeExtension/extension-iap). |   |
| Pathfinding           | [pathfinder (⭐28)](https://github.com/hypersurge/pathfinder)                      | Easy A\* pathfinding algorithm.                                                                                                                                                         |   |
| Sprite                | [haxe-aseprite (⭐20)](https://github.com/PongoEngine/haxe-aseprite)               | Parser for .ase and .aseprite files.                                                                                                                                                    |   |
| Steam                 | [SteamWrap (⭐86)](https://github.com/larsiusprime/SteamWrap)                      | Haxe native extension for the Steam API.                                                                                                                                                |   |
| Texture Packer        | [hxpk (⭐47)](https://github.com/bendmorris/hxpk)                                  | Port of the libGDX Texture Packer.                                                                                                                                                      |   |
| Tweening              | [actuate (⭐146)](https://github.com/jgranick/actuate)                             | A flexible, fast "tween" library.                                                                                                                                                       |   |
| \_                    | [YATL (⭐15)](https://github.com/Yanrishatum/yatl)                                 | Yet Another (Haxe) Tweening Library.                                                                                                                                                    |   |
| UI                    | [domkit (⭐72)](https://github.com/ncannasse/domkit)                               | CSS Components based strictly typed UI framework.                                                                                                                                       |   |
| \_                    | [flixel-ui (⭐138)](https://github.com/HaxeFlixel/flixel-ui)                       | GUI library for HaxeFlixel.                                                                                                                                                             |   |
| \_                    | [HaxeUI](http://haxeui.org/)                                                      | UI library with multiple framework backends (HTML5, Kha, OpenFL, PixiJS, WxWidgets, and a number of others as works in progress)                                                        |   |

## Articles

*   [Flash is dead, long live OpenFL!](http://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
*   [Flash is gone, what now?](https://www.linkedin.com/pulse/flash-gone-what-now-matan-uberstein/)
*   [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
*   [Building 42 games within a year — Insane game development](https://medium.com/@mknol/building-42-games-within-a-year-insane-game-development-5340d506068f)
*   [Porting to console via Unity](https://do-games.com/blog/the-adventure-pals-console-tech-part1)

## Other haxe lists

*   [awesome haxe (⭐83)](https://github.com/nadako/awesome-haxe)
*   [awesome snowkit (⭐123)](https://github.com/anissen/awesome-snowkit)
*   [awesome haxe js (⭐26)](https://github.com/MatthijsKamstra/awesome-haxe-js)

