---
title: Axonometric
tags:
  - medium/visual
  - method
  - roles/designer
  - roles/artists
  - used-by/designer
  - used-by/artist
  - tools/digital
  - tools/non-digital
aliases:
  - Architectural drawing
---
TO DO: Gameplay Axonometric, what 

also known as: Architectural drawing

## Classification
- #medium/visual 
- #method 
- #roles/designer #roles/artists 
- #used-by/designer #used-by/artist 
- #tools/digital #tools/non-digital 

## Intent

- "Communicate the composition of space" (Totten, p.54)
- Represent the three-dimensionality of an object

## Problem

### General

- You possess a drawing of an object, but its dimensions remain unclear in relation to the surrounding space. There is a **lack of three-dimensionality**, making it difficult to visualize the object when modeled.

### Specific

- For instance, you want to include a church in your level that players can enter. However, presenting only the outer front view, without revealing the interior in a 45-degree perspective, lacks depth.
- You prefer a drawing from an alternative viewpoint (possibly from the camera's perspective) to convey the building's purpose and display its architectural details.

## Solution Approach

## Solution Approach

- Use an **axonometric projection** to visualize the **3D space** of the object and its environment.

## Application

### Input

- Various types of [[Drawing]]s such as **plans, sections, simple [[Sketch]]es, more detailed sketches, and architectural drawings**
- Inspiration drawn from the **real world**
- Proficiency in understanding **3D space** and correctly representing it on paper or through a digital tool of your choice

### Application

- Determine the **desired angle** from which you want to depict your object (e.g., a bird's-eye perspective). Typically, a **45-degree angle** is chosen to convey three-dimensionality.
- Accurately draw your object from this perspective:
    - First, from the **exterior view** if necessary.
    - Second, and more importantly, with a **cross-section** through the object, revealing its interior.
- A more mathematical approach:
    - Take your object and draw a **coordinate system** within your drawing.
    - Project the outer corners of your object onto the coordinate system and **shift these points** along the three-dimensional axis.
    - Connect the points with lines to the original object, resulting in an accurate three-dimensional axonometric representation of your object.
	  
	  ![](assets/axonometric.png)
	  _(Geometrical Axonometric, Source: Wikipedia, [link](https://de.wikipedia.org/wiki/Axonometrie#/media/Datei:Haus-karo-axonometrie.svg) - @Ag2gaeh)_

### Output

- An **axonometric representation** of your object, which can be a **diagram**, **drawing**, or **sketch**.

### When to Use It

- When you want to **visualize the three-dimensional space** within your object.
- When you aim to **clearly communicate a detailed concept** of your object to your team, enhancing their understanding of your vision.

### Relevant Roles using this model
- #roles/artists [[Artist]] #used-by/artist 
- #roles/designer [[Designer]] #used-by/designer 

## Relevancy in the following processes
- [[Game Development]]
- [[Gamespace Prototyping]]
## Applicability

- - Like any drawing method, it is **beneficial for conceptualization** during the early stages of game development, especially before you begin modeling your objects.
- It serves as a useful tool for **team communication**.
- Apply this method when planning a **3D game** and need to arrange the spatial elements within your level effectively.

### Pros and Cons

**Pros:**
- It facilitates the team's understanding of your vision.
- It provides a valuable reference for artists, allowing them to model objects and locations as closely to the concept as possible.
- It can be implemented **both on paper and digitally**.
- Offers a more **technical understanding** of the level and assets.

**Cons:**
- Requires some level of artistic and mathematical knowledge.
- Demands a **precise working style** for accurate metrics.
- It's primarily a **conceptual design** and still requires further development.

## Relation with other Methods
- [[Drawing a Map]] because it shows part of the map in more detail
- Can include [[Symbols and Visual Language]] to enhance the sketch's communicative power

## Examples
- A sectional axonometric

  ![](assets/sectionalaxonometric.png)
  _(Source: [[Totten 2019 - An Architectural Approach of Level Design]], p.58)
  
- An axonometric drawing of a level with descriptions
![](assets/axonometricdrawing.png)
 _(Source: [[Totten 2019 - An Architectural Approach of Level Design]], p.59)

- The "computational anaglyphic method" that develops an axonometric 3D view based on the 2 images it was given as an input
  ![](assets/axonometricplane.png)
  _(Source: [link](Stereo_Orthogonal_Axonometric_Perspective.pdf) p. 220)_

- Game perspectives can also be shaped by axonometric/isometric views. Here's an example of that specific camera view:
  ![](assets/ageofempires.png)
  _(Source: Age of Empires, 1997-2023)_

## Relevant Tools
- [[Digital Art Tools]] like Photoshop, Procreate or any digital drawing tool
- [[Non-digital Design Tools]], pen and paper
- [[Computational Tools]] like proposed in [this](Stereo_Orthogonal_Axonometric_Perspective.pdf) paper

## Relevant Literature

[[Totten 2019 - An Architectural Approach of Level Design]]

Wikipedia about the definition of an Axonometric Projection: [[Axonometric Wikipedia Links]]

[[Stereo Orthogonal Axonometric Perspective for the Teaching of Descriptive Geometry]]

[[Isometric Projection in Game Development]]
