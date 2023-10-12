---
title: Massing
tags:
  - method
  - medium/visual
  - roles/designer
  - used-by/designer
  - used-by/artist
  - tools/digital
  - tools/non-digital
aliases:
---


also known as: 

## Classification
- #method 
- #medium/visual 
- #roles/designer 
- #used-by/designer #used-by/artist 
- #tools/digital #tools/non-digital 

## Intent

- Gain an understanding of space and the objects within it.
- Support the logic and function of a building or space.

## Problem

### General

- In architecture, one needs to comprehend the feel and logic of a space.
    - Is a room large or small, hidden or open, light or dark?
    - What is the relation between two rooms? Are they close together or far apart?
    - How do walls relate to one another?

### Specific

- The same principles apply to level design: You want to understand the underlying structure and spatial relationships of a building, place rooms in context, and grasp the overall atmosphere.
- Also consider how and when players will use the rooms/buildings.

## Solution Approach

- Divide the building/space into multiple rooms/sections and define their purpose.
- Experiment with the layout of the level until you achieve a coherent structure that makes sense for those using the building/space.

## Application

### Input

- A three-dimensional building or space that you want to comprehend and potentially redesign.

### Application

- Three massing methods:
    - **Dimensional**: Rotate, shape, or scale the object in all three dimensions.
    - **Additive**: Create more complex shapes by combining simple ones.
    - **Subtractive**: Remove a simple shape from a complex one. This can increase player interest when confronted with unique objects or spaces.
- Establish a hierarchy of importance among the masses you are analyzing. A complex, unusual shape can draw more player attention and become the central focus.
- Analyze the "readability" of your structure. A composition of many simple shapes is more readable than one composed of many complex shapes. Combining one complex shape with many simple shapes can draw more attention to the complex shape.
- Play with proportions and the center of gravity:
    - Thickness and Weight: Thicker and heavier objects naturally draw more attention.
    - Corners: Experiment with sharp and round edges. Rounded and complex corners attract more attention than simple ones. Break up structures with open corners.
    
- ##### Landscape Design
    
    - Shape the land and landscapes to support the flow of the level.
    - Consider nature: On a mountain, how does weather vary with elevation? Where do trees grow and where do they stop? Can it be rainy on one side of the mountain and sunny on the other? Where does water flow?
    - Landscape Sculpting workflow:
        - Layout: Create a simple diagram of the landscape with labels.
        - Blockout: Sculpt rough shapes for the landscape, paying attention to flow and scale.
        - Metrics: Measure travel times, heights, and traversable ramps/slopes.
        - Art pass: Sculpt and paint smaller details, apply set dressing.
    - Also consider the overall climate within that landscape; does it change?
    - Where do you place trees? Can they serve as walls?
    
    ![](assets/Alba_Blockout.jpeg) _(Alba Blockout phase of a landscape, Source: [link](https://medium.com/@ustwogames/the-environment-art-of-alba-a-wildlife-adventure-6bddd8b56955))
    
- ##### Path Design
    
    - Path Types:
        - Ledge Paths: Open on one side, closed on the other, e.g., hiking trails.
        - Cuttings: Closed on both sides, e.g., between mountains.
        - Ridge paths: Open on both sides and raised up, e.g., a trail on top of a mountain.
        - Switchbacks/zigzag paths: Alternating between the top three path types, not naturally occurring.
          
- ##### Composition
    
    - Visually organize your level.
    - Place objects based on dimensions:
        - Height: Consider their relative heights.
        - Density/spread: Determine their proximity.
        - Orientation: Analyze their facing directions.
        - Shape: Observe the variety or similarity of shapes.
    - Use landmarks as special points of interest that players will remember.
    - Employ vistas to provide an overview of the next scene or space.
    - Use sightlines (empty open space that allows viewing into the next space) and cover (protection from being spotted or attacked by enemies).

### Output

- Either a [[Prototype]] or just models (such as [[Asset]]s) in the early stages of prototyping (e.g., [[Blockout]]).
- A remodeled version of your level that considers all the points mentioned above.

### When to use it

- When you want to understand three-dimensional spatial compositions.
- When you want to make the space more interesting by using different compositions of objects.
- Fits well with prototyping.

### Relevant Roles using this model

- #roles/designer [[Designer]] #used-by/designer
- [[Roles/Artist]] #used-by/artist

## Relevancy in the following processes

- [[Gamespace Prototyping]] in the early stages.
- [[Combat Design]] to determine where to place vistas and cover.
- [[Iterative Map Design]] as it defines the map of the level in a specific way.

## Applicability

- Use it when you have at least sketches of your level. You should also have three-dimensional objects and spaces or at least an idea of what to include in the level.
- Ideal for detailed planning of space utilization.
- Offers many possibilities for adjustment according to player needs and your vision.

### Pros and Cons

**Pros**:

- Detailed approach.
- Offers various possibilities.
- Suitable for playtesting.

**Cons**:

- Requires technical capability, including access to software for shape creation.
- May consume significant time and effort.
- Focused on planning rather than implementation.

## Relation with other Methods

- [[Drawing a Map]] forms a more technical basis and serves as a foundation for reshaping the map based on various parameters.
- [[Level Parti]] precedes Massing and helps define shapes.
- [[Gym Scene]] builds upon Massing.
- [[Nintendo Power Method]] and [[Critical Path Analysis]] can analyze which shapes and rooms are important.
- [[Symbols and Visual Language]] can be developed through Massing and are emphasized by spatial composition.

## Examples

- Alba full map with landscape design, paths and spatial composition
  ![](assets/Alba_full.jpg)
 _(Source: [link]((https://medium.com/@ustwogames/the-environment-art-of-alba-a-wildlife-adventure-6bddd8b56955))_  
  
- Massing room structure analysis
  ![](https://i.imgur.com/GjyJHYW.png)
  _(Source: [link](http://www.presidentsmedals.com/Entry-19721))_

## Relevant Tools

- [[Digital Art Tools]] to generate 3D shapes and make blueprints of landscape objects that take to much time to design one by one, a 3D program like Blender
- [[Non-digital Design Tools]] like Sketching and measuring in the first steps
- [[Digital Collection Tools]] to save the designs
- [[Game Engines]] that import the designs

## Relevant Literature

[[Level Design Book]]: [Massing Chapter](https://book.leveldesignbook.com/process/blockout/massing)

[[Totten 2019 - An Architectural Approach of Level Design]] - Vistas