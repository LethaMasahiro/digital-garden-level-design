---
title: Nintendo Power Method
tags:
  - method
  - medium/visual
  - tools/digital
  - tools/non-digital
  - process/testing
  - process/developing
  - roles/engineers
  - roles/tester
  - used-by/designer
  - used-by/engineers
aliases:
---

## Classification
#method 
- #medium/visual 
- #tools/non-digital or #tools/digital 

## Intent

- To manage the pacing of your level on a macro-level.

## Problem

- Similar to the pacing diagram method as it deals with creating an engaging level with essential story points.
- It is important to revise your level with focus on the essential story points, what seems important to the players.
- How do you analyze the flow of your level? 
- You need to understand the level from the perspective of the player.

## Solution Approach

- The Nintendo Power method originated in the late 1980s in the game strategy and news magazine "Nintendo Power" ([[Totten 2019 - An Architectural Approach of Level Design]], p. 82-84).
- This method involves publishing maps of levels with important gameplay points marked as caption balloons ([[Totten 2019 - An Architectural Approach of Level Design]], p. 82-84).
- Designed as an overview to highlight critical gameplay points.
- It is valuable for game designers and developers, as it facilitates the analysis of player importance.

## Application

### Input

- Game beats.
- [[Map]] of your level.

### Application

- Combine the gameplay beats and mark them on the map.
- Analyze if the gameplay points create excessive density or restrict player breathing space.
- If the points densely populate the area, consider reducing them to allow more breathing room for the player.

### Output

- A [[Map]] with beats marked in your level.
- Spatial layout of your level.

### When to Use It

- Analyze the density of your level and assess what's crucial for the player.
- Add or remove story points to adjust pacing.

### Relevant Roles Using This Method

- #roles/designer [[Designer]] #used-by/designer 
- #roles/engineers [[Engineer]] #used-by/engineers 
- #roles/player [[Player]]

## Relevancy in the Following Processes

- Similar to the pacing graph method.
- [[Game Development]] designing step, after you already have a map.
- [[Gamespace Prototyping]] to evaluate your created map
- Evaluate your [[Combat Design]]
- Part of the [[Iterative Map Design]]
- Potentially useful in playtesting and post-development iterations to improve the level based on player feedback.

## Applicability

- Suitable for managing spatial layout, rather than focusing on timelines.
- Not suitable for pacing time events; use a linear [[Pacing Diagram]] for that purpose.

### Pros and Cons

**Pros**:

- Helps establish spatial relations.
- Allows analysis of player preferences and importance.
- Identifies densely packed areas.
- Facilitates the inclusion of safe spaces for exploration.
- Reveals player shortcuts and loopholes.

**Cons**:

- Lacks timing relations.
- A 2D map does not represent vertical spacing.
- Considering metrics can complicate and confuse a map.
- Uncertainty about when to use it; in design, after implementation, or during implementation? Decisions regarding the map's design status must be clarified.

## Relation with Other Methods

- Similar to a [[Pacing Diagram]], but with a focus on spatial relations.
- [[Drawing a Map]]
- Evaluates [[Pillars, Goals and Features]] regarding their significance in the level (are the goals of the level met?)
- [[Critical Path Analysis]] is similar to the Nintendo Power Method, as it evaluates the players actual spatial movements
- [[Behavior Diagram]] explains the player's and NPC behavior and can be influenced by the Nintendo Power method
## Examples


- 2D top-down with spawns and walls and paths marked
   ![](assets/nintendopowermethod.png)
  _(Source: [[Totten 2019 - An Architectural Approach of Level Design]], p. 82-84)

- 2D frontal view of Mario level with the varying ground levels and bubbles to mark gameplay beats
  ![](assets/nintendopowermethod2.png)
  _(Source: [[Nintendo Power Method]], p.82-84)_

## Relevant Tools
- [[Digital Art Tools]]
- [[Non-digital Design Tools]], Pen and Paper
- [[Digital Collection Tools]]
- [[Communication Tools]]

## Literature

[[Totten 2019 - An Architectural Approach of Level Design]]