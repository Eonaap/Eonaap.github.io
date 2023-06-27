---
title: "Wayward harbor"
date: 2021-11-01T03:21:36+02:00
draft: false
weight: 1
cover:
    image: /WaywardHarbor.jpg
---

{{< youtube id="UHS_B_eGyiU" >}}

## What is Wayward Harbor?
Wayward Harbor is a first-person horror game. Where you use a handheld mirror to escape from a terror revealing itself of the deeps of the ocean.

Haunted by a seemingly unstoppable force, you discover that your only way to survive is by using a family heirloom mirror which reveals a menacing threat. Explore through a dense environment and solve obstacles that lay in your way from escape.

Try the game on steam
{{< customiframe>}}

Or take a look at our itch page
{{< customiframe2>}}

## My role during the development
This game was made using Unreal Engine 4, by a team of 5.
During the 10 week development cycle, I focused on AI programming, creating the game loop, and cutscene and sound implementation.

The gameloop was made using C++ GameModeBase and its blueprint variant. It had to follow the story in the game, and change certain triggers and enable or disable the enemy
At certain points in the game, you got a checkpoint. When the player died, the gamemode would respawn the player at a specific place according to the checkpoint reached, together with the enemy.

The AI was dedicated to the behaviour of the enemy. This was created using a character C++ blueprint and the blueprint behaviour tree.
C++ was used to calculate when the enemy could see the player, so a flag could be set that could be used by the behaviour tree. Additionally, the enemy was only visible in the map when looking through a mirror object the player holds. These calculations and behaviour was also created in C++.
Beside the AI part, I was also responsible for the development of the enemy.

Other gameplay elements I worked on: 
- Physical doors
- movable cutscenes
- movement sounds variation
- prevention of object phasing