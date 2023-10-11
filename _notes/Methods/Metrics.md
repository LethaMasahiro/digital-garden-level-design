---
title: Method Layout
tags:
  - method
  - roles/designer
  - roles/tester
  - used-by/artist
  - used-by/engineers
  - used-by/designer
aliases:
---


also known as: 

## Classification
- #method 
- #roles/designer #roles/tester 
- #used-by/artist #used-by/engineers #used-by/designer 

## Intent

- Establish scale.
- Analyze data and build your game accordingly.
- Create relationships between objects in the level based on their size and volume.
- Create more realism or a unique style.

## Problem

- When planning and designing a level, character metrics must be considered in relation to the level, the environment, and other characters.
- Mechanics may rely on metrics to define the appropriate dimensions and required space.
- Having data to base decisions on can be advantageous.

## Solution Approach

- Apply Metrics to the game: Define the dimensions of characters and objects in relation to the landscape.
- Definition of metrics: The sense of scale, distance, and measurements across the entire level/game ([https://book.leveldesignbook.com/process/blockout/metrics](https://book.leveldesignbook.com/process/blockout/metrics)).
- Define mechanics with metrics in mind.
- There are different types of metrics:
    - **Player metrics** are actual numbers defining the three-dimensional scale of the player and their hitbox, including size, movement speed, maximum jump height, etc. This metric is mostly calculated by your game engine.
    - **Building metrics** are floor and room dimensions defined by the designer to influence the "feeling" of the level (e.g., creating narrow hallways to enhance the claustrophobic atmosphere).
    - **Puzzle metrics** determine the level's difficulty and structure, including the number of actions required to solve puzzles, and so on.
    - **Combat metrics** decide the scale of the combat space, the placement and distance between spawning points, enemy bounding boxes, etc.

## Application

### Input

- Ideas for mechanics or existing mechanics.
- Blocks representing your level or already modeled objects/characters.

### Application

- Adjust the scale of the blocks until you're satisfied with their size compared to your character.
- Define your metrics using numbers, particularly for building, combat, and puzzle metrics.
- Consider:
    - If your character is a child, the world may appear larger in their field of view. You can make objects bigger to emphasize this.
    - Metrics must allow characters to jump over obstacles or crawl under objects.
    - Metrics can be used to make your game more realistic (by scaling objects and characters similarly to the real world) or deliberately distort the scale to enhance the fantasy aspect of your game.
    - Metrics also define character hitboxes.

### Output

- A [[Blockout]] with the correct scales.
- [[Text]] defining the metrics.

### When to use it

- When constructing the concrete level after defining the mechanics.
- In your decision-making process and when you want to refine your level based on specific analytics.

### Relevant Roles using this model

- #roles/designer [[Designer]]
- #used-by/engineers [[Engineer]]
- #used-by/artist [[Artist]]
- #used-by/tester [[Tester]]

## Relevancy in the following processes

- [[Game Development]] in the pre-production and production phases.
- [[Combat Design]] when defining, analyzing, and refining the combat space.
- [[Gamespace Prototyping]] when creating a [[Blockout]].

## Applicability

- Helps define certain game rules.
- Metrics alone do not make a good game; they need to be tested and decisions based on trial and error and experience.

### Pros and Cons

**Pros**:

- Provides visual rules that everyone can follow.
- Adds atmosphere to a level.
- Universally applicable.
- Makes mechanics testable.

**Cons**:

- Metrics are just numbers that need careful calculation.
- Over-reliance on numbers may shift the focus away from testing.

## Relation with other Methods

- [[Axonometric]] because it adds metrics to a drawing.
- [[Drawing a Map]] can also incorporate metrics.

## Examples

There are common character sizes depending on the engine you use to make it coherent with the size of your level:
	- **Unity**: Bounding box is 1.0 x 1.8 m (or 1.0 x 2.0 m)
	- **Unreal 4**: Bounding box is 60 x 176 cm (half-height: 88)

## Relevant Tools
- [[Game Engines]]
- [[Computational Tools]]

## Relevant Literature

[[Level Design Book]] - [Metrics Chapter](https://book.leveldesignbook.com/process/blockout/metrics)


