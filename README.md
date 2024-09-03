This is Druid Mechanics course for Unreal GAS, Game Play Abilities.

The course description


This is the most comprehensive Unreal Engine course available. If you want to learn how to architect a fully-functional RPG game, this course will give you the ability to do so with an expandable code base, architected with AAA quality code. If you've ever wondered where to draw the line between C++ and Blueprints, this is the course for you. If you've ever wanted to create an RPG complete with a stats system, abilities, leveling up, spells, attributes, menus, all while keeping your code base clean and following best practices, this is the course for you. If you want to step up your Unreal Engine development capabilities and better understand the inner workings of the engine, this course is for you. If you have plans to make your own serious game with interconnecting systems, involving attributes, abilities, level ups, enemies and AI, and coded for multiplayer, this is the course for you!

In this course, we will create a top-down RPG style game, filled with systems architected using Unreal Engine's built-in Gameplay Ability System (GAS). This is where you will learn how to architect a shipped game, and code it expertly so it can be easily expanded, upgraded, and maintained. We follow SOLID coding principles, and balance the Blueprint/C++ ratio in a way that AAA shipped games do, such as Fortnite. My experience with AAA shipped game code, as well as consultations with industry veteran developers has allowed me to reveal to you the way a real shipped game's code base looks like. If you've ever wondered how much of a game can be kept in Blueprint versus C++, look no further. This course is the answer.

NOTE: This course involves programming in C++, which involves the use of an Integrated Development Environment (IDE) such as Visual Studio, Rider, or VSCode. The IDE used in this course by me will be Rider, but this IDE is not a requirement for students to follow the course. You can use any IDE of your choice.

The assets in this game project were made specifically for this course, and will be provided in an asset pack. This includes:

Characters, including Aura, the main character, as well as enemy characters including Goblin Warriors, Goblin Rangers, a Goblin Shaman, Red and Black Demons, the Ghoul, and a Shroom.

A modular dungeon pack that can be pieced together to make basic dungeons

A waypoint shrine and obelisks

Particle Niagara System Effects, including explosions, level up effects, slingshot rocks, hit impacts, electricity beams, fireballs, fire bolts, flames, stars for stun effects, and more!

Sound effects for enemies, footsteps, spells, and more!

Textures for the HUD, including high-quality buttons, frames, dynamically-animated spell globes, progress bars, XP bar, and more!

Full animation sets for Aura and all enemies

Much more!

In this course, we will be covering the following topics:

Setting up a Top-Down Project from scratch

Enemy and item selection with outline effects

Proper use of OOP and inheritance to create a character class hierarchy

Intro to the Gameplay Ability System and the core classes that comprise it

Custom Gameplay Ability System Components and Attribute Sets, and how to replicate Attributes

All important settings for all GAS classes and components

How to use Attributes for player stats, including Primary Attributes:

Strength (increases physical damage)

Intelligence (increases magical damage)

Resilience (increases Armor and Armor Penetration)

Vigor (increases Max Health)

Secondary Attributes, based off of primary attributes and other custom variables:

Armor (reduces damage taken, improves Block Chance)

Armor Penetration (ignores percentage of enemy Armor, increases Critical Hit Chance)

Block Chance (change to cut incoming damage in half)

Critical Hit Chance (chance to double damage plus critical hit bonus)

Critical Hit Damage (bonus damage added when a critical hit is scored)

Critical Hit Resistance (reduces critical hit chance of attacking enemies)

Health Regeneration (amount of Health restored every 1 second)

Mana Regeneration (amount of Mana restored every 1 second)

Max Health (maximum amount of Health obtainable)

Max Mana (maximum amount of Mana obtainable)

Vital Attributes - things like Health and Mana, which are dependent on all the other attributes

Gameplay Effects - classes in the GAS system used to apply changes to attributes

Gameplay Tags - an essential part of GAS, which allows us to identify qualities, attributes, abilities, character classes, and any other thing we can imagine

Game UI - how to handle complex UI in an RPG game efficiently, in an organized, modular, and scalable manner. We cover different UI paradigms, from MVC (Model View Controller) and MVVM (Model View ViewModel, using Unreal Engine's new ViewModel feature)

Full Attribute and Spell Menus, with upgrade abilities, spell trees, locked spell levels, spell upgrades by ability level, and more

Attributes - how to use Gameplay Attributes to represent player stats, and incorporate them into the gameplay mechanics by creating an Effect Application pipeline, allowing for calculations and results caused by phenomena in the game, such as combat damage

Gameplay Abilities - the heart of GAS. We create all manner of types of gameplay abilities to handle the casting of spells, handling important capabilities of the player character and enemy AI, and how to configure different abilities to suit your needs.

Different RPG Classes - we implement different character RPG classes including the Ranger, Warrior, and Elementalist, and do so in an easily-scalable manner so you can have any number of character class types in your game

Damage and Combat - we implement a full RPG style combat system with different damage types, damage resistances, and debuffs corresponding to damage types, and encode these calculations into our damage pipeline. All attributes, damage types, resistances and debuffs are functional in this game.

All combat mechanics are displayed in some form of visual feedback to the player. This includes floating text for damage, changing color based on custom criteria, floating text to inform of critical hits, blocked hits, and critical blocked hits. We also implement knockback and stun mechanics in response to lightning damage, incapacitating the character/enemy, as well as fire debuffs, where characters are set ablaze and take fire damage while burning.

Enemy AI - We implement the enemy behavior using Unreal Engine Behavior Trees and the Environment Query system (EQS) to provide customized behavior for the Ranged, Warrior, and Elementalist enemy types.

Enemies can cast spells and summon AI minions

Fading geometry when it gets in the way of the camera for a top-down game

Ability Cost and Cooldown (spells spend Attribute resources - in this game, spells cost Mana)

Fully functional HUD with Equipped Spells, displaying spell cooldown timers, and experience (XP)

The ability to assign Abilities to different inputs in the spell menu (assign FireBolt to the 1 key and Electrocute to the Left Mouse Button, swap them back, etc.)

Experience and Level-Up System - We craft an experience system, awarding XP for eliminating enemies, and leveling up when reaching XP thresholds for various abilities. XP and Level are displayed in the HUD, and Level Up messages and effects are as well. Leveling up is associated with gaining Attribute Points and Spell Points, which can be used to upgrade Attributes and Spell abilities in the Attribute and Spell Menus respectively, as well as topping off Health and Mana upon Leveling Up. (Basically, you will see enough examples of how to use this system that you'll be able to expand it with any functionality you want for your own games)

Passive Spells - Spells that you can equip which remain active while they are equipped.

A variety of Offensive Spells, showcasing different examples and features of GAS, including FireBolt, Electrocute, Arcane Shards, and FireBlast.

Saving Progress and Level Transitions

Intermediate/Advanced Unreal Engine topics, including custom Async Tasks, Ability Tasks, Blueprint Function Libraries, Asset Managers, Singletons (and why these are only good for a VERY select few cases), custom Gameplay Effect Contexts, Net Serialization, Struct Ops Type Traits, C++ Lambdas, game mechanics algorithms, and oh, so much more.

How to choose which functionality should go into C++ versus Blueprint - This is one of the most valuable lessons, and is taught all throughout the course. Students often ask me "which functionality should go in C++ versus in Blueprint?" This course is my answer. This is a serious-scale project foundation with over 100 hours of video, and no filler. The project is architected with approximately 50% Blueprints and 50% C++. I show you which functionality should be on the C++ side, which functionality is more appropriate for Blueprints, and why.

SOLID Coding Principles and code architecture - We keep our code base clean in this project. Another question I often get is "Is this best coding practice?" This course is my answer to this question. This is an example of code you would see in a AAA game, shipped to millions of players. Maintaining clean and modular code is essential to a serious game project that needs to be scalable, expandable, modular, maintainable, testable, performant, and efficient. This course will show you how.

This is not a beginner course. I expect you to already understand the C++ programming language and have at least created one Unreal Engine C++ project.

This course is my best course yet, and I'm very proud to bring you the Unreal Engine 5 - Gameplay Ability System - Top Down RPG course, the result of nearly a year of painstaking development, research, consultation with professionals, and asset creation. After taking this course, you will understand Unreal Engine far better than the average developer, and you'll be empowered to create your own well-architected projects, large and small, and you'll bring value to your team, your company, your solo venture, and anyone/anything else you grace with your skillset.

Join the course, and invest in the biggest leap of your game development career.

Stephen Ulibarri, founder of the Druid Mechanics Game Developer Community

This course project is created in Unreal Engine version 5.2. Updates are periodically added to ensure compatibility with newer engine versions.

What you’ll learn
Unreal Engine's Gameplay Ability System
Multiplayer Gameplay Mechanics
Creation of a full RPG with Combat, Experience and Level Ups, Enemies, Spells, Menus, Game Saving, and much more
SOLID coding principles and AAA quality code architecture
How to determine which code goes in Blueprints and which code goes in C++ for optimal performance in a shipped game
Scalable, modular, maintainable, and expandable code that can serve as the foundation for any serious game
All core features of the Gameplay Ability System
Code debugging tools and practices
Are there any course requirements or prerequisites?
Knowledge of the C++ Programming Language
Fundamentals of Unreal Engine C++ - have at least created one Unreal Engine C++ project
Who this course is for:
Those who wish to know how to architect a scalable and shippable game in Unreal Engine
Those who wish to know how to implement gameplay Attributes, Abilities, Experience, Level Ups, and how to maintain these in a clean code base
Those who wish to know how to handle game UI for complex systems in an efficient manner
Those who wish to create their own RPG, MOBA, Shooter Game, or any other type of game involving attributes, skills, spells, or other custom mechanics
Those who wish to know how to implement enemy AI with Behavior Trees and Environment Queries (EQS)
Those who have Unreal Engine experience and are looking to expand their skillset to create shippable games
Those who are looking for a comprehensive course on the Gameplay Ability System (GAS) so they can use it in their own game projects
Hobbyists and Professional Game Developers alike will benefit from this course
AAA developers who need to learn the fundamentals of GAS for their team's game project
Leaders of game development projects who need to understand how GAS works in Unreal Engine, its capabilities, limitations, and costs on time and effort for developers
Teams who need to architect their game project in a scalable manner, so it will be easily maintainable post-launch
Anyone who has created some basic Unreal Engine projects and is ready for some next level greatness!
