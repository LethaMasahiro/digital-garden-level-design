---
title: Pillars
---


also known as: Design Pillars, Design Goals and Features

## Classification
- #method 
#medium 
#process 
#roles 
#used-by 
#tools 
...

## Intent
- Design along fixed principles and variable decisions
- Allow for the interplay between fixed decisions and decisions that can be changed

## Problem

- How to design a game/level and which decisions should play a role
- How to structure a game design document

## Solution Approach

- Your design decisions consist of four parts: 
	- Pillars (fixed decisions)
		- No decision during design and implementation of the game development process should be against the pillars.
		- Can be seen as classical restrictions
	- Goals (more abstract and not measurable)
	- Features (changeable decisions)
	- Context (things that need to be considered when making the specified decisions)

## Application

### Input
- All decisions written down somewhere
- Ideally, an outline of your game design document

### Application

- Divide your decisions into the four specified parts:
  
	- Pillars: Your fixed decisions and basic design principles of your game. Iterate over them to get the big vision. Set them as fixed before production phase and don't change them!
		- You can use prosa instead of a technical description so that everyone understands the principles
		  
	- Design Goals: The goals you want to achieve with every decision. Show what you mean with every resource possible, e.g. with pictures, references, sound ("showing is better than telling" - Anferson, 2016)'
		- You don't need to use only text and keep in mind that you're trying to grasp an abstract idea. Features are then described later with the goals in mind.
		  
	- Features: In line with design pillars and implement the goals. Be as technical and as descriptive as possible. Consists of:
		- Name
		- Vision Statement ("As a player, I can ... with ..., in order to feel ...")
		- Technical Description (define and describe technical decisions)
		- Interfaces (describe the connections to other features, systems etc.)
		- References (Examples, Mockups, Moodboards, where you draw inspiration from)
		- Risks (+ alternatives if you have any)

### Output
- An outline of the decisions made, organized, sorted and described in detail
- A better organisation for the game design document

### When to use it
- In the Game Developing process ideally before production phase
- Any time to refactor your game design document, but the decisions should've been made already ideally

### Relevant Roles using this model
- #roles/designer [[Designer]] #used-by/designer 
- [[Artist]] #used-by/artist 
- [[Engineer]] #used-by/engineers 
- [[Writer]] #used-by/writer 
- [[Tester]] #used-by/tester 

## Relevancy in the following processes
- [[Game Development]]
- [[Combat Design]] when the decisions influence the combat system

## Applicability
- Good with specifically defining your goals and fixes decisions
- Usable in the early design and decision stages
- Only helps in decision making, collecting resources and testing (refering back to what you decided to do)
- Doesn't implement your game directly
- Can limit your thinking process

### Pros and Cons

Pros:
- Gives you clear goals and definitions (also on a technical level)
- Can always be referred back to
- Fixes decisions, sorts and ranks them
- Can also be used without a game design document (Diablo 3 developers didn't have a gdd but still defined seven design pillars)

Cons:
- Design Goals are very abstract and can be hard to define
- Might limit creative freedom and make the design process too theoretical

## Relation with other Methods
- Can define the structure of the [[Game Design Document]] which is about decision making
- [[Reference Collection]], [[Mood Boards]] as possible references for features

## Examples

- Diablo 3 Design Pillars (https://www.purediablo.com/diablo-3s-seven-design-pillars):
	- Approachable
	- Powerful Heroes
	- Highly customizable
	- Great item game
	- Endlessly replayable
	- Strong setting
	- Cooperative Multiplayer
	  
- The Last of Us Game Pillars (https://www.gamedeveloper.com/design/design-pillars-the-core-of-your-game):
	- Crafting
	- Story
	- AI Partners
	- Stealth

## Relevant Tools
- [[Digital Collection Tools]]

## Relevant Literature

Andersen, 2016; "Create Your First Game Design Document", 2020

https://orioldedios.github.io/Game-Design-Pillars/#:~:text=In%20essence%2C%20Game%20Design%20Pillars,that%20make%20a%20cohesive%20design.

https://www.purediablo.com/diablo-3s-seven-design-pillars

https://www.gamedeveloper.com/design/design-pillars-the-core-of-your-game