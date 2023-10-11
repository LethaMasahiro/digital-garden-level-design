---
title: Critical Path Analysis
tags:
  - method
  - medium/graph
  - medium/visual
  - process/designing
  - process/planning
  - process/testing
  - process/developing
  - roles/designer
  - roles/manager
  - used-by/designer
  - used-by/manager
  - tools/digital
  - tools/non-digital
aliases:
---


also known as: 

## Classification
- #method
- #medium/graph #medium/visual 
- #process/designing #process/planning #process/developing #process/testing 
- #roles/designer #roles/manager 
- #used-by/designer #used-by/manager 
- #tools/digital #tools/non-digital 

## Intent

- Design level flow.
- Analyze which paths a player takes.

## Problem

- A Game Designer has designed a level, but how do they know which paths a player takes?
- What is the quickest and most direct route to completing a level?
- For instance, in "Hitman", how can the hitman reach their target in the shortest way possible, given numerous alternatives?

## Solution Approach

- Use the Critical Path Method (CPM) to identify the critical path
- Determine the player's chosen path and identify areas which unvisited or uninteresting to the player

## Application

### Input

- A map or initial layout of the level

### Application

- Critical Path Method (CPM): 
	-  Mark the start and end points of the level on the map.
	- Identify and number important gameplay beats and points crucial to the story and level progression.
	- Draw a line between the start and end points, passing through all marked gameplay beats in the correct order, following the level's flow.
  
	  ![](criticalpath.png)
	  _(An example of a critical path in the Level Design Book. Source: [link](https://book.leveldesignbook.com/process/layout/criticalpath))
	
	- Consider marking areas untouched by the critical path to assess their importance to the level.
	- Experiment with the level's design, including the option to remove areas not essential to the critical path to observe the impact.
	  
	  ![](criticalpathunnecessary.png)
	  _(How the example level would look when deleting all "unnessessary" areas. Source: [link](https://book.leveldesignbook.com/process/layout/criticalpath))
  

### Output

- A remodeled version of your level , [[Map]] with comments in form of [[Text]]
### When to use it

- When your level is too packed with unnecessary stuff.
- When you want to reduce the level to its core gameplay.
- When you want to increase the levels pacing and limit the exploration.
- Can be used before and after blocking out and prototyping the level, but the idea of a map has to be present.

### Relevant Roles using this model

- #roles/designer [[Designer]] #used-by/designer 
- #roles/manager [[Manager]] #used-by/manager  (because the CPM isn't limited on level design, but can determine roadmaps as well)

## Relevancy in the following processes

- [[Combat Design]]
- [[Iterative Map Design]]
- [[Gamespace Prototyping]]
- [[Game Development]] the designing part
- [[Software Engineering Workflow]] Design phase

## Applicability

- When you want to understand the flow of a level and how a player moves
- To determine which elements are important to the level if they are not on the critical path
- Is not limited to level and map design, but it can also aid decisions on the criticality of a project step regarding its resources and time limit. Managers can use the CPM to decide on the order in which the project steps should be taken under or what's to time-consuming and costly.

### Pros and Cons

**Pros:**
- Encourages effective spatial thinking.
- Focuses on core gameplay and player paths.
- Enhances understanding of player behavior.

**Cons:**
- When to use it exactly? Before or after blocking out and prototyping the level?
- "Building around a critical path usually results in a 'video game-y' feeling" ([[Level Design Book]])

## Relation with other Methods
- [[Drawing a Map]]
- [[Nintendo Power Method]], because this is also a form of analysis

## Examples

- Deathloop critical path:
  
  ![](criticalpathdeathloop.png)
  _(Source: [[Level Design Book]])_

## Relevant Tools
- [[Digital Art Tools]]
- [[Non-digital Design Tools]]
- Any tool that lets you draw a path through a map

## Relevant Literature

- [Critical path method (CPM)](https://web.archive.org/web/20181024032348/http://web.stanford.edu/class/cee320/CEE320B/CPM.pdf)
- [Level Design Book: Critical Path](https://book.leveldesignbook.com/process/layout/criticalpath)