---
title: Axonometric
---


also known as: Architectural drawing

## Classification
- #medium/visual 
- #method 
- #roles/designer #roles/artists 
- #used-by/designer #used-by/artist 
- #tools/digital #tools/non-digital 

## Intent
- "Communicate the composition of space" (Totten, p.54)
- Represent the threedimensionality of an object

## Problem

### General
- You have the drawing of an object but its dimensions don't become clear in relation to the space surrounding it. There is no three dimensionality and therefore it's hard to imagine what the object looks like when modeled.

### Specific
- e.g. you want to add a church in your level that can be entered, but just having the outer front view without showing what the inside looks like in a 45 degree view lacks depth
- You would rather have another drawing from another perspective (maybe also from the camera perspective) that communicates the purpose of the building and shows its building blocks 

## Solution Approach

- Use an axonometric to help visualize the 3D space of the object and its surroundings

## Application

### Input
- Any types of drawings like plans, sections, simple sketches, more detailed sketches, architectural drawings
- Inspiration from the real-world
- Knowledge about 3D space and how to correctly visualize it on paper or in a digital tool of your choice

### Application

- Define at which angle you want to draw your object from (e.g. you can view the church from a bird perspective), typically a 45 degree angle is chosen to depict threedimensionality
- Draw your object from this perspective as accurately as possible
	- Once from the outer view if you would like
	- And once, the more important part, with a cut right through the object so that you see inside the object
- A more mathematical approach:
	- Take your object and draw a coordinate system inside your drawing
	- Project the outer corners of your object on the coordinate system and shift these points along the three-dimensional axis
	- connect the points with lines to the original object. Tada, you just made an accurate three dimensional axonometric of your object!
	  
	  ![](https://i.imgur.com/hm41KT9.png)
	  (Geometrical axonometric, Wikipedia https://de.wikipedia.org/wiki/Axonometrie#/media/Datei:Haus-karo-axonometrie.svg @Ag2gaeh)

### Output
- An axonometric of your object, [[Diagram]]

### When to use it
- If you want to visualize the three-dimensional space within your object
- If you want to communicate a detailed idea of your object to your team and make them understand better what you imagined

### Relevant Roles using this model
- #roles/artists [[Artist]] #used-by/artist 
- #roles/designer [[Designer]] #used-by/designer 

## Relevancy in the following processes
- [[Game Development]]
- [[Prototyping]]
## Applicability
- Just like any drawing, it is good for conceptualization and the early stages of developing a game before you model your objects
- Also a good method to communicate with your team
- Apply it when you plan a 3D game and need to plan the spatial arrangements of your level

### Pros and Cons

Pros:
- It helps the team to understand what you imagined
- It's a good reference for artists to model the objects ans location as close to the concept as possible
- It can be done on paper and digital

Cons:
- it requires a little bit of artistic and mathematical knowledge
- It also requires an exact style of work if you want to get the metrics right
- It's just a concept design and still has to be built

## Relation with other Methods
- [[Drawing a Map]] because it shows part of the map in more detail
- [[Paper Prototype]] ?
- Can include [[Symbols and Visual Language]]

## Examples
- A sectional axonometric

  ![](https://i.imgur.com/U78pHNe.png)
  (Totten, p.58)
  
- An axonometric drawing of a level with descriptions

![](https://i.imgur.com/bJe82gX.png)
(Totten, p. 59)

- The "computational anaglyphic method" that develops an axonometric 3D view based on the 2 images it was given as an input
  ![](https://i.imgur.com/puVHexm.png)
  (https://files.eric.ed.gov/fulltext/ED557273.pdf p. 220)

- Game perspectives can also be shaped by axonometric/isometric views. Here's an example of that specific camera view:
  
  ![](https://i.imgur.com/4RoW9eg.png)
  Age of Empires, 1997-2023

## Relevant Tools
- [[Digital Design Tools]] like Photoshop, Procreate or any digital drawing tool
- [[Non-digital Design Tools]], pen and paper
- [[Computational Tools]] like proposed in this paper https://files.eric.ed.gov/fulltext/ED557273.pdf 

## Relevant Literature

Totten [[Totten 2019 - An Architectural]]

Wikipedia about the definition of an Axonometric Projection https://en.wikipedia.org/wiki/Axonometric_projection https://de.wikipedia.org/wiki/Axonometrie#/media/Datei:Haus-karo-axonometrie.svg

https://files.eric.ed.gov/fulltext/ED557273.pdf 

https://pikuma.com/blog/isometric-projection-in-games
