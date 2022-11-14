---
title: Unity 2D With C# - Complete Game Dev Course
description: Create the complete 2D survival game in Unity with C#. Learn best practices and patterns.
author: Filip Jerga
authorImage: https://thrangra.sirv.com/Final_Unity_2D_Small.jpg
coverImage: https://thrangra.sirv.com/Final_Unity_2D_Small.jpg
date: "2022-01-25"
---

**What is Unity?**

Unity is a cross-platform game engine. The Unity editor is supported on Windows, macOS, and the Linux platform. In contrast, the engine currently supports building games for over 25 platforms, including mobile, desktop, consoles, and virtual reality.

**What are we going to build?**

The course covers the development of one production-ready game. The type of game is 2D survival with a top-down view.

**Project - Undead Survival**

The main effort of this course is to show the viewer how to build a complete game from scratch. The game's goal is to survive as long as possible with infinite waves of enemies coming at the game protagonist.

The most important parts of the course are:

**Scriptable Objects**

Scriptable objects will be essential in creating the Statemachine, Ability system, and Action delegation. Scriptable objects make the project reusable and modular.

**State Machine**

Statemachine is the brain of the AI system. Every NPC can have different states (run, attack ...), while only one state can be active at a time. Every state can have multiple actions. Action is the behavior.

For example, the Enemy has a "Patrol" state. A patrol state can have two actions. One action is to provide movement to the enemy. Another action is to change the animation of the enemy to the walk.

The third component of the Statemachine is a condition. Condition is a boolean statement. When the statement or multiple statements are resolved as "true" the current state can be transited to the new one.

For example, if an enemy is in the "patrol" state and the "spot player condition" is resolved as "true", then an enemy can go to the "attack" state.

Enemies will have a straightforward state machine. More complex state machines will be applied to boss entities.

**Ability System**

A player and enemies can have different abilities. Each ability has stats, such as damage, cooldown, range, effect, and many others. Each ability is created as a scriptable object, which can be easily reused and changed to the required needs. There are two main types of abilities, passive and active ones. Passive ones are the abilities that are played automatically at a specific interval. Active ones need to be activated by some external input, such as a key-stroke of the player.

**Other Parts**

The course also covers other essential topics such as the spawning mechanism for the enemies, the UI system to display applied damage, game time, and other vital stats. There is also damage and health system. Next, the course covers the creation of the start/options menu with the options to navigate and choose different protagonists. The game is finished when the hero dies. When this happens, the score screen is displayed, and the game can be replayed infinitely.

Many other smaller topics will be covered in the course.

**Main Goal**

The main goal of the course is to teach how to create reusable systems that can be used in different games. The course focuses on the reusability of each component.
