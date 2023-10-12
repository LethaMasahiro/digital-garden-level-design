---
title: Game Design Document
tags:
  - process
aliases:
---

---

also known as: 

## Classification
#process 

## Intent

- Offer the player the right amount of challenge.
- Control enemy encounters.
- Design high-intensity pacing areas.

## Problem

- You have your game idea but want to include combat. How can you do that effectively?
- How do you make combat exciting and versatile without it feeling repetitive?
- Sometimes, you want to decide on the mechanics of the game based on the combat you'd like to have. The other way is possible too, when you'd like to base the combat on already defined mechanics. What can the player do with enemies when they have a limited amount of ammunition?

## Process Steps

### 1. Get familiar with the key concepts of combat

- Explore different types of combat:
    - **Classic Combat**: Close-range fights, focused on studying enemy movements and tactics rather than relying on powerful weapons, includes aim-aid and a lot of dodging.
    - **Military Realism**: Long-range fights, emphasizing fast reaction and speed, precise aiming is crucial.
    - **Modern Combat**: Mid-range battles with a focus on managing damage (healing), slower player movement.
      
- Understand common player combat styles:
    - **Rusher**: Quickly advances along the main path, engaging in close to mid-range combat.
    - **Sniper**: Prefers control and overview, engaging in long-range combat.
    - **Ninja**: Avoids direct paths, favors stealth and flanking.
    - **Opportunist**: Explores the environment for unpredictable outcomes, seeks high interactivity.
      
- Consider key combat concepts to inform your design:
    - Design NPC types with distinct behaviors, motivations, skills, and weaknesses.
    - Plan how encounters with NPCs occur, including hostility levels.
    - Determine cover placement and types, influencing combat difficulty (e.g., static, moveable, dynamic, durability).
    - Define the duration of combat sequences and the presence of enemy waves.
    - Strategically schedule combat encounters in the level to balance pacing.
    - Design combat fronts, rears, and flanks to allow various player approaches.
    - Create safe spaces for players to regroup.
    - Decide on allowable weapons and mechanics, along with available ammunition.
    - Incorporate vantage points to enhance player perspective.
    - Explore how allied NPCs can assist in combat.
      
- Use the following methods in combat design:
    - [[Pacing Diagram]]
    - [[Drawing a Map]]
    - [[Behavior Diagram]]
    - [[Molecule Diagram]]
    - [[Reward Schedule]]
      
- Tools used in this step: [[Non-digital Design Tools]], [[Digital Diagram Tools]], [[Communication Tools]], [[Digital Collection Tools]], [[Communication Tools]].
    

### 2. Blockout a test area

- Test combat mechanics and dynamics in a [[Gym Scene]] or [[Blockout]].
- Relevant Tools: [[Game Engines]].
- Relevant Roles: #roles/designer [[Designer]], #roles/engineers [[Engineer]].

### 3. Place enemies

- Determine enemy placement within the scene.
- Decide on the level of detail for enemies (mechanics testing vs. fully detailed).
- Relevant Tools: [[Game Engines]].
- Relevant Roles: #roles/engineers [[Engineer]].

### 4. Playtest and iterate

- Test the combat sequence in the [[Prototype]] scene.
- Start testing early to identify and address issues promptly.
- Iterate over the design and blockout as needed.
- Relevant Tools: [[Game Engines]], [[Digital Collection Tools]], [[Communication Tools]].
- Relevant Roles: #roles/engineers [[Engineer]], #roles/tester [[Tester]], #roles/designer [[Designer]].

![](assets/haloenemies.png) _Enemy types in Halo (2001)_

![](assets/wavedesign.png)Possible wave design as in [[TychoBolt (K., Alex) 2020 - In Pursuit of Better Levels]]

![](assets/converheight.png) 
Height of cover _(Source: [[TychoBolt (K., Alex) 2020 - In Pursuit of Better Levels]])_

## Applicability

- As part of the [[Game Development]] process, this is a small but important process.
- Essential for a versatile game experience if combat is included in your level.

### Pros and Cons

**Pros**:

- Very practical and applicable.
- Direct sources for combat design in levels: "Level Design Book" and "LD - In pursuit of better level design" (provide links).
- Creates an exciting gameplay experience and aligns well with level pacing when done correctly.

**Cons**:

- Difficult to balance and fine-tune.
- Involves numerous decisions and complexities.
- Poorly executed combat design can significantly impact the game negatively.

## Related Processes

- Part of the [[Game Development]] process (pre-production and production phase)
- Also part of [[Gamespace Prototyping]] since it is part of the level

## Relevant Literature

[[Schell 2014 - A Book of Lenses]]: Challenges lense

[[Level Design Book]]

[[TychoBolt (K., Alex) 2020 - In Pursuit of Better Levels]]

[[Combat in Games]]