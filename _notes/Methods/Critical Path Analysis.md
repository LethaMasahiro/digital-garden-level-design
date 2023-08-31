---
title: Critical Path Analysis
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

- Design level flow 
- Analyze which paths a player takes

## Problem

### General
- A Game Designer has designed a level, but how do they know which paths a player takes?
- What is the quickest and most direct route to completing a level (LD - In Pursuit of better levels)

### Specific
- How does the Hitman in "Hitman" get to his victim in the shortest way possible? There are many alternative way paths but which way leads to the shortest completion time?

## Solution Approach

### General
- Use the Critical Path Method (CPM) to find the critical path
- 

### Specific

## Application

### Input
- A map or initial layout of the level

### Application

- Critical Path Method (CPM): 
	- Mark the start end end of the level on the map
	- Mark and number important gameplay beats and points essential to the story and progression of the level
	- Draw a line between the start and the end point, hitting all marked gameplay beats in the right order and following the flow of the level
  
	  ![](https://i.imgur.com/xgbnGI2.png)
  An example of a critical path in the Level Design Book (https://book.leveldesignbook.com/process/layout/criticalpath)
	
	- You can mark the areas that are not touched by the critical path aswell, deciding if they are important to the level at all
	- Play around with the design of the level. You can also delete areas not important to the critical 
	  path and see for yourself how the level turns out
	  
	  ![](https://i.imgur.com/LnwWiwW.png)
	  How the example level would look when deleting all "unnessessary" areas, https://book.leveldesignbook.com/process/layout/criticalpath
  

### Output
- A remodeled version of your level , [[Map]]
### When to use it
- When your level is too packed with unnecessary stuff
- When you want to reduce the level to its coreplay
- When you want to increase the levels pacing and limit the exploration
- Can be used before and after blocking out and prototyping the level, but the idea of a map has to be there

### Relevant Roles using this model
- #roles/designer [[Designer]] #used-by/designer 
- #roles/manager [[Manager]] #used-by/manager  (because the CPM isn't limited on level design)

## Relevancy in the following processes
- [[Combat Design]]
- [[Iterative Map Design]]
- [[Prototyping]]
- [[Game Development]] the designing part
- [[Software Engineering Workflow]] Design phase

## Applicability
- When you want to understand the flow of a level and how a player moves
- Decide which elements are important to the level if they are not on the critical path
- Can not only be used for level and map design, but make decisions on the criticality of a project step regarding its resources and time limit. Managers can use the CPM to decide on the order in which the project steps should be taken under or what's to time-consuming and costly.

### Pros and Cons

Pros:
- Thinking effectively about space
- Focus on core gameplay and paths
- Understand the player better

Cons:
- When to use it exactly? Before or after blocking out and prototyping the level?
- "Building around a critical path usually results in a 'video game-y' feeling" (Level Design Book)

## Relation with other Methods
- [[Drawing a Map]]
- [[Nintendo Power Method]]? Showing the important gameplay beats and building around them

## Examples

- Deathloop critical path:
  
  ![](https://i.imgur.com/zKCwLs3.png)
  (Level Design Book)
  
- Make own example

## Relevant Tools
- [[Digital Design Tools ]]
- [[Non-digital Design Tools]]
- Any tool that lets you draw a path through a map

## Relevant Literature

- Critical path method (CPM) https://web.archive.org/web/20181024032348/http://web.stanford.edu/class/cee320/CEE320B/CPM.pdf
- https://book.leveldesignbook.com/process/layout/criticalpath
- 