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
- Structure your level
- spatial relations of your level and good overview
- know where to put level objects, gates, fights and where to set your gameplay beats and story points in a spatial sense
- create dynamic between story and space
- "arrangement of gamespaces" (McMillan, Azar), "link spaces together"

## Problem

General:
- describe spatial relations -> use graphs
- connect nodes with each other to show their relation
- don't want to show exact metrics but rather describe the relations between the nodes

Concrete:
- A game level has different gamespaces that are conected through tunnels, gateways
- Need to show direct transferals to gamespaces or indirect views on another game areal (e.g. on a platform)
- How a player moves through the level. Is there a one-way or can the player go back? What does it do for the level pacing when one can go back or not, or look at the arena before a big fight happens?

## Approach/ Solution
- create a molecule diagram and make a planar map out of it that concentrates on the relations and not on the metrics
- try to avoid linearity in your level (room-to-room)
- think of vertical space as well
- nodes and edges

Graph Theory:
- Domination Theory: nodes have an area of effect and can overlap with other nodes ("zones of play" that can interfere with other zones (above them, right after them, change something in one room and the other one changes), make sure that the overlapping makes sense (adding a wall in the overlapping might solve the problem of spawn- and fight zones being too close))
  ![](https://i.imgur.com/5YMCS0y.png)
  (Areas of play in Halflife, https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design)
    - Spanning Trees: Nodes are connected by many lines so that there are multiple ways to visit every node, therefore applying a spanning tree shows the shortest and most optimal route (helps in defining where to put pickups, spawns and understand player behavior, where they move)
  - Steiner Points: Steiner tree is a tree that looks for the shortest connection between nodes, sometimes like a hub (players use these Steiner points since it's the shortest connection between gamespaces, they can skip parts of the spanning tree with this)
    - can be higher points that are the only route for pickups as well
    - teleporters
    - points of interest to oversee the area ![](https://i.imgur.com/QQkERQn.png)
       (Krom's Canyon Steiner Points Z and X, https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design)

Hard and soft gates:
- When is the player allowed to return?
- Hard gates: pass it once and never rreturn?
- What are soft gates again?


## Application

### Input
- Decision which gamespaces you have in your level
- Pen and Paper or digital tool
- graph theory knowledge

### Application. 
- draw your gamespaces as nodes, the size can vary based on the criticality and importance to the level or story. You can always name them and take nodes on the sides as well
- Think of a way to connect these nodes with lines. You can start very abstract with just nodes and lines.
- There can be multiple lines leading to one node and vice versa, doesn't have to be 1:1 to create variety, hypergraph
- transfer this graph to a more diverse sketch/interpretation, thinking about overlapping spaces to create vertical spacing. Think about the direction the player can move in and if it's a one-way or can be used multiple times.
  ![](https://i.imgur.com/YiRzGHV.png)
  (interpretation of a molecule diagram, https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design)
  - avoid linearity since it becomes boring to just jump from room to room
  - consider the shortest routes a player would take (ultimately tested with players in the implementation phase?)
  - Include Steiner points as higher platforms, points of interest, teleports, shortcuts on purpose that can also be unlocked later in the level maybe
  - Feel free to color your map to structure it
  - be aware of overlapping gamespaces and divide critical gamespaces by gates, walls, put them further away,...
  - you can make your edges thicker to highlight the importance of the connection between the nodes (don't use it for showing the actual size of the gateway!)
  - define your relations by using dotted lines (spaces can be viewed from another), arrows (showing direction), Thick lines (direct paths)

![](https://i.imgur.com/IBV4NBz.png)
other example how to draw and explain the diagram (Totten)

### Output
- Molecule diagram, Hypergraph (?)
- interpretation of the diagram (sort of a map)

### When to use it

- #process/designing 
- #process/planning  
- always roll back to it and iterate with prototyping since this is just on paper
- doesn't have to be fixed but having it before you start implementing (prototyping) gives you good structure

### Relevant Roles using this method
- #roles/designer  [[Designer]]
- #roles/artists [[Artist]]
- #roles/engineers [[Engineer]]


## Relevancy in the following Processes
- [[Prototyping]]
- [[Game Development]] designing?
- [[Game Development]] Planning?

## Applicability
- good to have in planning and designing process
- not for actual map creating since it only shows spatial RELATIONS
- not real-world application, more of a concept
- communication tool and good base to think about assets and art as well
- works well with the pacing of your level since it can support your storytelling

### Pros and Cons

Pros:
- visual language
- strong communication tool, also between roles
- good base for an actual map
- can be revisited and improved, doesn't have to be fixed
- therefore good with agile and waterfall approaches

Cons:
- doesn't show actual metrics
- 2-D and therefore difficult to display vertical spatial relationships
- not interchangeable with your maps and still conceptual

## Relation with other Methods
- Map Drawing

## Examples
- Molecule Diagram halo4
  ![](https://i.imgur.com/Z0eYeZM.png)
(Totten)

- 

## Relevant Tools
- Pen and Paper
- Communication Tool like Teams or Slack
- Document Folder Structure to store the Diagram
- some [[Digital Design Tools]] to draw and share

## Relevant Literature

https://www.gamedeveloper.com/design/the-metrics-of-space-molecule-design

Totten Book