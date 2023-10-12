---
title: Pillars
tags:
  - method
  - medium/text
  - process/planning
  - roles/designer
  - roles/manager
  - roles/writer
  - used-by/designer
  - used-by/artist
  - used-by/engineers
  - used-by/writer
  - used-by/tester
  - tools/digital
  - tools/non-digital
aliases:
  - Design Pillars
  - Design Goals
  - Design Features
  - Features
---


also known as: Design Pillars, Design Goals and Features

## Classification
- #method 
#medium/text 
#process/planning 
#roles/designer #roles/manager #roles/writer 
#used-by/designer #used-by/artist #used-by/engineers #used-by/writer #used-by/tester 
#tools/digital #tools/non-digital 

## Intent

- Develop a game or level with a balance of fixed principles and variable decisions.
- Encourage an interplay between established principles and modifiable choices.

## Problem

- How do you effectively design a game or level while determining which decisions to prioritize?
- How do you structure a comprehensive game design document?

## Solution Approach

- Organize your design decisions in four key categories:
  
    - Pillars (Fixed Decisions):
        - Fundamental, unchanging principles that serve as the core of your game design.
        - Should guide all design and implementation decisions.
        - Often, they are considered classical constraints or restrictions.
          
    - Design Goals:
        - Abstract objectives linked to each decision.
        - Use various resources like images, references, and sound to convey your goals.
        - Emphasize "showing is better than telling."
          
    - Features (Changeable Decisions):
        - Align with design pillars and work toward achieving the design goals.
        - Include specific details such as name, vision statement, technical description, interfaces, references, and risk assessment.
          
    - Context:
        - Considerations and factors that must be taken into account when making specific design decisions.

## Application

### Input

- A record of all design decisions.
- Ideally, an outline of your game design document.

### Application

- Divide your decisions into the four categories:
	- Pillars: Fixed principles that define the fundamental aspects of your game. Ensure that these remain unchanged throughout production.
	        - Consider using prose to explain these principles in a way that is accessible to all team members.
          
	- Design Goals: Abstract objectives tied to each decision. Use various media to illustrate your goals.
	        - Remember that you're trying to convey abstract ideas.
	        - Features should be described later with these goals in mind.
	          
	- Features: These should align with the design pillars and help achieve the design goals. Provide technical and descriptive details, including:
	        - Name
	        - Vision Statement ("As a player, I can... with..., to feel...")
	        - Technical Description (definition and description of technical decisions)
	        - Interfaces (connections to other features, systems, etc.)
	        - References (Examples, Mockups, Moodboards, sources of inspiration)
	        - Risks (identify potential issues and propose alternatives if applicable).
	          
	- Context: Collect other things you need to consider. They will define the context of your decisions regarding specific artifacts or more general decisions.
		- For example, point out the uniqueness of your level and justify why it has to be in the game.
		  
- You can enhance the definition of your overall level with this approach or specific aspects of the game.
          

### Output

- An outline of the decisions, well-organized, categorized, and described in detail, typically in a [[Document]] or [[Text]]ual form.
- Enhanced organization for the [[Game Design Document]].

### When to Use It

- Ideally, in the game development process before the production phase.
- Whenever there's a need to refine your game design document, although decisions should ideally have been made beforehand.

### Relevant Roles Using This Model

- #roles/designer [[Designer]] #used-by/designer
- [[Artist]] #used-by/artist
- [[Engineer]] #used-by/engineers
- [[Writer]] #used-by/writer
- [[Tester]] #used-by/tester

## Relevancy in the Following Processes

- [[Game Development]] in the planning, designing and testing phase
- [[Combat Design]] when decisions impact the combat system.
- [[Gamespace Prototyping]] considers the decisions made

## Applicability

- Effective for defining goals and fixed principles.
- Best suited for early design and decision-making stages.
- Facilitates decision-making, resource collection, and testing but does not directly implement the game.
- May impose theoretical constraints on the design process and can limit your creativity.

### Pros and Cons

**Pros**:

- Provides clear goals and definitions, including technical aspects.
- Offers a reference point throughout development.
- Identifies and categorizes fixed decisions.
- Useful even without a formal game design document (e.g., Diablo 3's seven design pillars).

**Cons**:

- Design Goals can be highly abstract and challenging to define.
- May restrict creative freedom, leading to a more theoretical design process.

## Relation with Other Methods

- Defines the structure of the [[Game Design Document]], which is essential for decision-making.
- May involve elements of [[Reference Collection]] and [[Mood Boards]] as references for features.

## Examples

- **Diablo 3 Design Pillars** (source: [Pure Diablo](https://www.purediablo.com/diablo-3s-seven-design-pillars)):
    
    - Approachable
    - Powerful Heroes
    - Highly customizable
    - Great item game
    - Endlessly replayable
    - Strong setting
    - Cooperative Multiplayer
      
      
- **The Last of Us Game Pillars** (source: [Game Developer](https://www.gamedeveloper.com/design/design-pillars-the-core-of-your-game)):
    
    - Crafting
    - Story
    - AI Partners
    - Stealth

- **Axis-aligned Top-Down Camera** Design Decision
  
	- Pillars: Axis-aligned Top-Down Camera
	- Goals: Sense of Verticality & Depth
	- Features: Weather Effects, ...
	- Context: For this view to take full effect, the game world must have buildings with various heights. ...

## Relevant Tools

- [[Digital Collection Tools]]
- [[Communication Tools]]
- [[Non-digital Design Tools]]

## Relevant Literature

[[Andersen 2016 - How to Write a Game-changing Audio Design Document today]]

[[Game Design Pillars]]

[[Diablo 3 - Seven Design Pillars]]

[[Design Pillars - The Core of your Game]]