# ZZT 64
An honest attempt at a ZZT clone for the Commodore 64.


## Summary

**ZZT** is one of the first successful programs in the genre of the "Game Creation System", or **GCS** for short. Most GCSes in the 80s and early 90s were created as a "simulation" of real game design tools, from sprite editors to music composers, which made these programs too complicated for anyone to use, and ate up precious RAM space to boot. Garry Kitchen's GameMaker is a great example: Although it was impressive on paper, it had an intimidating learning curve and allowed only 3553 total bytes of space to work with, which is *nonsense*.

ZZT set itself apart from other GCSes by being as stupidly simple as possible:
* Only CGA ANSI text characters can be used
* Gameplay mimicks several terminal-based Roguelikes
* Various built-in enemies are provided with simple flags attached for properties
* Various Sokoban-inspired puzzle objects are provided, including pushers, pullers, teleporters and more
* Custom objects can be placed in the world
* Game worlds consist of "boards", placed in a grid pattern
* Quest items are included, such as scrolls, keys, and doors
* Easy-to-learn scripting language called ZZT-OOP


## Creativity

ZZT offers users a blank canvas to paint whatever you want on the boards. Using just the built-in objects, you can make a simple game or puzzle with very little effort. Sometimes you just want to place down a bunch of built-ins and a bunch of ammo pickups and go nuts, and ZZT would let you do this. This was done using a mouse/joystick and keyboard, and since the editor is in the same text mode as the game, you can create something, then immediately test it out.


## The C64 conversion

Such a simple premise as ZZT should be a cinch for the C64. Some corners may have to be cut for CPU and memory reasons (looking at you, star throwing tigers) but the most commonly used elements should be included. The C64 has a keyboard and joystick already, so input will not be a problem.

ZZT64 will likely be in C using cc65 with inline ASM for the CPU-intensive bits. Using cc65 allows for the use of a RAM expansion card, and this would be period correct, but would put ZZT64 out of reach to a lot of C64 users as REUs are quite expensive, even at the time of this writing.


## Purpose

Simply put, I want to get better at programming, especially on older computers with simpler instruction sets and limitations. And, I think ZZT is the best text-based game ever made.


## Timeline

There is *no* timeline for this, this may not even get started until months after I write this, so who knows? I've got to learn the development tools available first, and how the Commodore 64 actually works on a *very* low level before I can start with anything. However, mockup screens can be made with David Murray's PETDraw, which should give a general idea on what the game will look like.


## Progress

Development hasn't even started yet, so watch this space.
