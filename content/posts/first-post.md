---
title: "Rebuilding Hraal"
date: 2025-11-02
draft: false
---

Six years ago, barely knowing how to write a line of code, I decided my first game would be an isometric, procedurally generated RPG with a living, breathing world. No design doc. No plan. I just sat down and started building. This is what every game dev does, they think up some grand masterpiece like a gigantic open-world simulation with zero experience. Before this, I had read a book on C#. I don't believe I finished it, but I was ready to make games.

Enter Hraal. I sat down and figured out in my tiny brain how isometric movement would work, how tile placement works, the pain of dealing with layers when it comes to isometric art placement. I did crazy things like create giant lists of objects in memory that weren't efficient at all. You name all the bad things, I did them.

{{< figure src="https://github.com/volyth/volythblog/blob/main/assets/images/hraal-iteration-1.png?raw=true" caption="An early version with placeholder art." >}}

Over the next couple of years, I'd step away, come back, step away again. Slowly, I realized I wasn't making a game, I was accidentally building an engine. The codebase became a snapshot of my evolution as a programmer: from barely functional garbage to slightly less garbage code that somehow worked.

The final thing I added was a tile-based lighting system that ate up weeks of my life. After that, I walked away and never came back. I went on to mess with Godot, Unity, and other game engines and let the pile of unfinished games grow.

{{< figure src="https://github.com/volyth/volythblog/blob/main/assets/images/hraal-iteration-3.png?raw=true" caption="Final version with tile-based lighting" >}}

It's late 2025 now. Hraal, originally the game's working title, is now the name of my isometric engine. But I'm not refactoring the old code. I'm rebuilding it from scratch, using what I learned the first time around to do it right.

**What's Changing:**
- Starting fresh with .NET 9 / MonoGame 3.8.4.1
- Building with ECS architecture from day one
- Proper separation between engine and game logic

This is me documenting that process.

There will be a game (this is currently being planned, yes, actually planned). But the foundation starts now.
<div style="padding-bottom: 5rem;"></div>
