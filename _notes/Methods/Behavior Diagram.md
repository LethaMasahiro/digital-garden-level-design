---
title: Behavior Diagram
---

also known as: Behavioral Diagram, Dynamic View, Activity Diagram, Use Case Diagram, State Machine Diagram, ...?

## Classification
- #method 
- #roles/designer 
- #used-by/designer #used-by/engineers 
- #medium/diagram 
- #tools/digital #tools/non-digital 

## Intent
- Describe the behavior of game objects and their interaction with each other according to general scenarios and specific use cases
- find a unified modeling language (UML) that the team understands

## Problem

### General
- Game objects act in a certain way, can be independent from the player and time-based, can be repeated, can be invoked by the player and can be a unique action
- It's necessary to describe these actions and how it evolves the situation around them as well as how it changes the objects themselves
- It's also important to know the different scenarios changing the object

### Specific
- Take a level in a stealth game for example, how would you want to guide the player through the level?
- What can the player do and what are the specific consequences of their actions? Will a guard be alarmed if the player steps into the light? What will the guard do? Is it game over immediately or will the player have the chance to hinder the guard from reaching out to fellow guards? Does the player have to fight?

## Solution Approach

### General
- A behavior diagram is used in UML (Unified Modeling Language), a model langage used to communicate designs to a vast range of people who know the language. It's intuitive and easy to understand.
- A behavior diagram is a mix of:
	- A Use Case diagram: depiction of a single interaction from the user with the system, bubbles/elipses show the actions by the different actors within the system, the actors as well the actions are connected through lines to show who is participating in the actions
	- An Activity Diagram: Model of processes and activities within a system. Is not bound to a single Use Case but instead depicts the system as a whole. Models a system with its actions step-by-step (https://highered.mheducation.com/sites/0077110005/student_view0/glossary.html)
	- A State Machine Diagram: (also known as State Diagram, Statechart) Depicts the system in various states that the system can enter and leave. Instead of the first two diagrams, it describes what a system IS rather than what it DOES. (https://www.omg.org/spec/UML/2.2/Superstructure/PDF)
	  
- Difference of Behavior Diagrams and Structural Diagrams:
	- Structural Diagrams emphasize on the objects and attributes within a system, focus on the static nature of objects (what it IS, not how it REACTS), including class diagrams and composite structure diagrams
	- Behavoral Diagrams highlight the dynamic behavior between objects, emphasize change and how a system can evolve and change through time, shows how objects work together
	  (https://www.visual-paradigm.com/guide/uml-unified-modeling-language/behavior-vs-structural-diagram/)

- Use any type of above-mentioned behavior diagram or mix them to find the best depiction of your system for your scenario

### Specific

- If you want to abstractly pin down how the player can interact with your level, draw a behavior diagram.
- You can start by defining the player as an actor and NPCs as other actors, defining what the player can do in the level that affects the NPCs and how they react.
- Use State Diagrams for example for the world that changes with whatever the player decides to do. For example if they have the choice to damage an object, the room they are in becomes damaged from the action. If they decide to persuade a guard and it does not work, the guard can become angry which is also a state that triggers certain actions.

## Application

### Input
- Definiton of actors, game objects and the setup of the level

### Application
- Write down the actors as stick figures
- Draw the possible actions of the actors as ellipses/circles and connect these to the actors that are affected by it
- Think about the consequences that come out of the actions and define them as states or new actions themselves. Again, decide who is affected by it and how it shapes the level or the world
- This way you pin down possible outcomes and have a better understanding of how to guide players through your story/ how to guide them in the direction you want them to go

### Output
- A behavior diagram that can be shared with teammates, digital or non-digital, [[Diagram]]

### When to use it
- Deciding on gameplay cues, possibilities, storytelling incentives
- Open-world or more story-based? Give the player freedom or guide them?
- Be prepared for unpredictable player behavior
- Reduce bugs und unforeseen outcomes/loopholes

### Relevant Roles using this model
- #roles/designer [[Designer]] #used-by/designer 
-  [[Engineer]] #used-by/engineers 

## Relevancy in the following processes
- [[Game Development]] Decision making process?

## Applicability
- decision-making
- making a plan
- it's hard to pin down a complex level to a limited design language
- The interaction is time-based, has nothing to do with spatial decisions
- Good to test your level for potential outcomes and player behavior, especially if you include players and more team members to collaborate
- When exactly to use it? In parallel to reference collection for example? After drawing a map?
- Can be used together with the [[Nintendo Power Method]] and [[Pacing Diagram]]s because they describe the level progress with story elements to build anticipation, something that can be supported by actions and reactions of game objects on a micro level

### Pros and Cons

Pros: 
- Based on UML which is a universally accepted modeling language (https://www.uml.org/what-is-uml.htm) and therefore easy to communicate with in a team
- Break down complex interaction structures to simple geometric forms and explain them in short phrases
- Reduce complexity of game development
- Adds to building anticipation when used together with Pacing Diagrams
- Good addition to artistic choices because it's very story- and interaction-based

Cons:
- UML has negative sides as well which also apply to Behavior Diagrams in level design (for further insides, you can visit https://www.tutorialride.com/software-architecture-and-design/uml-diagrams.htm https://ieeexplore-ieee-org.eaccess.tum.edu/abstract/document/6822324)
- There can always be loopholes that you don't see and the players will exploit, this is not fail-prove
- Doesn't show spatial relationships (rather use maps for that)

## Relation with other Methods
- [[Nintendo Power Method]] and [[Pacing Diagram]] are good additions
- [[Reward Schedule]] can be used in addition to match the rewards the player receives (actions that can also be depicted as circles/ellipses within a behavior diagram)

## Examples
- Game Example: Do one yourself
  
- Example of a State Diagram in a Serious Game proposed in this paper: https://www.researchgate.net/profile/Martin-Hanneghan/publication/267801341_Towards_a_Domain_Specific_Modelling_Language_for_Serious_Game_Design/links/5512d8900cf268a4aaeb3061/Towards-a-Domain-Specific-Modelling-Language-for-Serious-Game-Design.pdf
  
  ![](https://i.imgur.com/4VaHUKJ.png)

- A Use case diagram for a restaurant
  ![](https://i.imgur.com/uNkumVK.png)
  https://en.wikipedia.org/wiki/Use_case_diagram

## Relevant Tools
- Model-driven Engineering -> Framework proposed by Stephen Tang et al. in "Towards A Domain Specific Modelling Language for Serious Game Design"
- [[Digital Diagram Tools]]

## Relevant Literature


https://www.researchgate.net/profile/Flavio-Silva-18/publication/283654063_A_Systematic_Review_of_Game_Design_Methods_and_Tools/links/59f0dce7458515bfd07fb211/A-Systematic-Review-of-Game-Design-Methods-and-Tools.pdf p. 10 (25)

https://www.uml.org/what-is-uml.htm

Towards A Domain Specific Modelling Language for Serious Game Design https://www.researchgate.net/profile/Martin-Hanneghan/publication/267801341_Towards_a_Domain_Specific_Modelling_Language_for_Serious_Game_Design/links/5512d8900cf268a4aaeb3061/Towards-a-Domain-Specific-Modelling-Language-for-Serious-Game-Design.pdf