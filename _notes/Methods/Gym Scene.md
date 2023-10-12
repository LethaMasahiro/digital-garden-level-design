---
title: Gym Scene
tags:
  - method
  - process/testing
  - process/developing
  - tools/digital
  - roles/engineers
  - roles/designer
  - used-by/engineers
  - used-by/designer
aliases:
---

Also known as: 

## Classification
- #method 
- #process/testing #process/developing 
- #roles/designer #roles/engineers 
- #used-by/engineers #used-by/designer 
- #tools/digital 

## Intent

- Gain a practical overview of your level.
- Test your metrics, character controller, and mechanics.
- Evaluate how your level utilizes space effectively.

## Problem

- You have a conceptualized level and want to test it.
- Mechanics, game plans, and the level layout are already defined.

## Solution Approach

- Utilize a gym scene to test your planned and designed elements.
- Verify if everything functions as planned and aligns with your vision.

## Application

### Input
- A map (optional)
- Decisions about the game mechanics about to be implemented and tested
- Decisions on the interactable objects, not necessarily the finished assets

### Application

- Build a level in your [[Game Engines]] of choice, doesn't have to look like your planned level but should include all important elements of your gameplay
- Roughly define the blocks and objects as obstacles, interactables or other important elements. These can be [[Blockout]]s.
- Try to play the character and challenge the metrics and mechanics to find bugs as early as possible.

### Output

- A platform with objects that you can use for testing what you had in mind, a form of [[Prototype]].
- Different variations of your mechanics, e.g. different platforms for different jumping techniques, moving platforms.

### When to use it

- For testing your mechanics and ideas

### Relevant Roles using this model
- #roles/designer [[Designer]] #used-by/designer 
- #roles/engineers [[Engineer]] #used-by/engineers 
- Collaboration between these

## Relevancy in the following processes

- [[Game Development]] Panning, Production and Testing Phase
- [[Gamespace Prototyping]] maybe in the blockout phase

## Applicability

- It's not an actual level, so avoid using it when you intend to create your level from a map. Instead, employ it to test the limits of your mechanics and discover new ideas that expand those mechanics.

### Pros and Cons

**Pros**:

- Provides a quick way to create a practical testing environment without requiring polished assets.
- Identifies bugs and limitations early in development.
- Encourages the discovery of unforeseen possibilities.

**Cons**:

- Not a complete level, limiting its assessment to functional analysis.
- Challenging to evaluate storyline and gameplay beats; it's primarily suited for exploration and mechanics testing.

## Relation with other Methods

- The outputs from [[Massing]] are used to build the gym.
- Can test mechanics related to [[Symbols and Visual Language]]
- Tests out the [[Pillars, Goals and Features]] regarding their mechanics decisions.


## Examples
- ![](assets/gymscene.png)
  random blocks placed to test mechanic (Alex K. @TychoBolt, 2020)

## Relevant Tools

- [[Game Engines]]

## Relevant Literature

[[TychoBolt (K., Alex) 2020 - In Pursuit of Better Levels]]

