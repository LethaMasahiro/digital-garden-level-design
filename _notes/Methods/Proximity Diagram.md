---
title: Proximity Diagram
---


also known as: 

## Classification
- #method 
- #medium/graph #medium/visual #medium/diagram 
- #roles/designer 
- #used-by/designer #used-by/artist #used-by/engineers 
- #tools/digital #tools/non-digital 

#### Intent

- Similar to Molecule Diagrams.
    - Structuring the level using a detailed, language-coded approach.
    - Providing a spatial overview of the level.
    - Determining the placement of level objects, gates, encounters, gameplay beats, and story points in a spatial context.
    - Establishing a dynamic relationship between narrative and space.
- Coordinating space requirements alongside space allocation.

## Problem

- In contrast to Molecule Diagrams, you specifically want to describe spatial relationships, e.g. the size of the rooms/game spaces or the connection of specific rooms
- Establishing connections between game spaces within the level based on how important their connection is.

## Solution Approach

- Create a [[Molecule Diagram]] but convey additional meaning through node size and connections.
- Utilize all the principles of the Molecule Diagram while enhancing its meaning.

## Application

### Input

- Decisions regarding which game spaces are present in the level and require additional information.
- Pen and paper or digital tools.
- Knowledge of graph theory.

### Application

- Construct a Molecule Diagram.
    
- Adjust the sizes of nodes based on:
    
    - Spatial metrics, such as larger representations for rooms of 50m² compared to rooms of 30m².
    - The significance of the game space within the level.
      
- Modify the thickness of connections between nodes to reflect their importance.
    
    - Utilize different line types to signify accessibility between spaces (normal lines) or one-way visibility from one space to another (dashed lines). Apply creativity and only depict what you wish to communicate.
      
- Apply the tips and principles from Molecule Diagrams.
    

### Output

- A proximity [[Diagram]].
- An interpretation of the diagram, such as [[Map]].

### When to Use It

- In the planning and designing phases.
- When you want to imbue a Molecule Diagram with additional layers of meaning.

### Relevant Roles Using This Model

- #roles/designer [[Designer]] #used-by/designer
- [[Roles/Artist]] #used-by/artist
- [[Engineer]] #used-by/engineers

## Relevance in the Following Processes

- [[Gamespace Prototyping]]
- Planning and designing phases of [[Game Development]]
- [[Combat Design]]

## Applicability

- Similar to the [[Molecule Diagram]], with added details.

### Pros and Cons

- Similar to the [[Molecule Diagram]].

## Relation with Other Methods

- Closely related to the [[Molecule Diagram]].
- May lead to [[Drawing a Map]] as a subsequent step after constructing the diagram.
  
## Examples

- One example of transferring a Proximity Diagram to a Map
  ![](proximitydiagram.png)
  _(Source: [[Totten 2019 - An Architectural Approach of Level Design]], p.133)_

## Relevant Tools
- See [[Molecule Diagram]]

## Relevant Literature

[[Totten 2019 - An Architectural Approach of Level Design]]

[[The Metrics of Space - Molecule Design]]
