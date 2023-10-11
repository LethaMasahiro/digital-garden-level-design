---
title: Molecule Diagram
tags:
  - method
  - medium/diagram
  - medium/graph
  - medium/visual
  - tools/non-digital
  - tools/digital
  - process/planning
  - process/designing
  - roles/designer
  - roles/engineers
  - roles/artists
aliases:
  - HUB spaces
  - Sandbox Gamespaces
---

also known as:
## Classification
#method 
#medium/diagram
#medium/graph
#medium/visual 
#tools/non-digital
#tools/digital
#process/planning 
#process/designing
#roles/designer 
#roles/engineers 
#roles/artists

## Intent

- Structure your level.
- Define the spatial relations within your level and gain a clear overview.
- Determine where to place level objects, gates, fights, and key gameplay beats and story points in a spatial context.
- Create a dynamic relationship between story and space.
- Establish the "arrangement of gamespaces" (_Source: [link](https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design)_), "link spaces together."

## Problem

### General:

- Describe spatial relations using graphs.
- Connect nodes to illustrate their relationships without focusing on exact metrics.

### Specific:

- In a game level, various gamespaces are interconnected through tunnels and gateways.
- Need to visualize direct transitions to gamespaces or indirect views of other game areas (e.g., on a platform).
- Determine how a player moves through the level, including one-way paths, backtracking options, and the impact on level pacing.

## Approach/ Solution

- Create a molecule diagram and convert it into a planar map that emphasizes relationships rather than metrics.
- Avoid linearity in your level design (e.g., room-to-room progression).
- Consider vertical space and interactions between nodes and edges.

#### Graph Theory:

- **Domination Theory**: Nodes have areas of effect and can overlap with other nodes ("zones of play"). Ensure that overlapping makes sense (e.g., adding walls to prevent interference between overlapping zones).
   ![Areas of play in Halflife](areas-of-play-halflife.png)
    _(Source: [link](https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design))_
    
    - **Spanning Trees**: Connect nodes with multiple lines to create optimal routes (helps define item placements, spawns, and player behavior).
      
    - **Steiner Points**: Identify key connection points (e.g., hubs) where players often traverse shorter paths (useful for pickups, shortcuts, teleports). ![Krom's Canyon Steiner Points Z and X](steiner-points-chrom.png) 
      _(Source: [link](https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design))_

#### Hard and soft gates:

- Determine when players can return to specific areas.
- Consider whether gates are "hard" (pass once) or "soft" (reversible).

## Application

### Input

- Decisions about the gamespaces in your level.
- Pen and paper or digital tools.
- Knowledge of graph theory.

### Application

- Represent gamespaces as nodes, varying their size based on importance to the level or story. Add labels and side nodes.
- Connect nodes with lines, allowing for abstract connections.
- Multiple lines can lead to one node, and vice versa, creating variety (hypergraph).
- Transform this graph into a more diverse sketch, considering overlapping spaces for vertical diversity. Think about player movement directions, one-way paths, and repeated traversal. 
  ![Interpretation of a molecule diagram](molecule-diagram.png) 
  _(Source: [link](https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design))_
  
    - Avoid linearity, as it can become monotonous.
    - Analyze the shortest routes players might take (ultimately tested during implementation with players?).
    - Include Steiner points as higher platforms, points of interest, teleports, or intentional shortcuts that may unlock later in the level.
    - Use colors to structure your map.
    - Address overlapping gamespaces by adding gates, walls, or increasing distances.
    - Adjust edge thickness to emphasize connections (do not use it to indicate actual gateway size).
    - Use dotted lines (spaces can be seen from another), arrows (showing direction), and thick lines (direct paths) to define relations.

Other examples of how to draw and explain the diagram can be found in Totten's work ([[Totten 2019 - An Architectural Approach of Level Design]]).

##### Hub Spaces

- Hub spaces define the central spatial points where the player can access different levels from.
- They are considered safe spaces for the player to not feel tense.
- A typical structure of a hub-based game:
  ![](hubspacesstructure.png)
  _(Source: [[Totten 2019 - An Architectural Approach of Level Design]], p.135)_

##### Sandbox Gamespaces

- Are defined by open-world spaces that still maintain certain limits.
- Players can explore the world in their own pace.
- The nodes are more scattered and follow a non-linear structure.

### Output

- Molecule [[Diagram]], [[Hypergraph]]
- Interpretation of the diagram (a sort of [[Map]]).

### When to use it

- In the designing and planning processes.
- Always refer back to it and iterate with prototyping, as it serves as a foundational reference.
- While not fixed, having it before implementing (prototyping) provides a structured foundation.

### Relevant Roles using this method
- #roles/designer  [[Designer]]
- #roles/artists [[Roles/Artist]]
- #roles/engineers [[Engineer]]


## Relevancy in the following Processes
- [[Gamespace Prototyping]] - Step 2 (Create a Bubble Diagram or Flowchart)
- [[Game Development]] Planning and Designing phase
- [[Combat Design]]
- [[Iterative Map Design]]

## Applicability

- Suitable for the planning and designing processes.
- Not intended for actual map creation, as it primarily depicts spatial relations.
- More of a conceptual tool than a real-world application.
- Functions as a communication tool and provides a foundation for considering assets and art.
- Supports the pacing of your level and enhances storytelling.

### Pros and Cons

**Pros**:

- Provides a visual language for spatial relationships.
- Effective communication tool, facilitating collaboration between roles.
- Serves as a valuable foundation for creating an actual map.
- Allows for revisiting and improvement, without the need for a fixed representation.
- Suitable for both agile and waterfall development approaches.

**Cons**:

- Does not represent actual metrics.
- Primarily 2-D and challenging to convey vertical spatial relationships.
- Not interchangeable with your maps and remains a conceptual tool.
## Relation with other Methods

- [[Drawing a Map]]
- [[Proximity Diagram]]

## Examples

- Molecule Diagram halo4
  ![](molecule-diagram-halo4.png)
  _(Source: [[Totten 2019 - An Architectural Approach of Level Design]])_

## Relevant Tools

- [[Non-digital Design Tools]] like Pen and Paper
- [[Communication Tools]] like Teams or Slack
- [[Digital Collection Tools]] Document Folder Structure to store the Diagram
- Some [[Digital Art Tools]] to draw and share

## Relevant Literature

[[The Metrics of Space - Molecule Design]]

[[Totten 2019 - An Architectural Approach of Level Design]], Chapter: Molecule Level Spaces