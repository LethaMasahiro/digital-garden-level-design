---
title: Software Engineering Workflow
---

also known as: 

## Classification
#process 

## Intent
- How to develop software: Simple workflow that develops a product from beginning to end
- Software engineering doesn't have an end but is rather a cycle
- Create value for a company

## Problem

### General
- want to develop software, what is the first step, where to start?
- Is there a recipe? How can the work be segregated to increase efficiency?
- Concentrate on the development process, not the marketing. Especially focus on the designing, planning, and developing phase.

### Specific
- Games are also products and can therefore gain inspiration from classic software engineering.
- See the product (the game) through from beginning till end
- Understand which roles are needed in which step, what the inputs and outputs are and how everything works together

## Process Steps

![](https://i.imgur.com/OVdQQDd.png)
Software Engineering Workflow by Ralf Engelschall (2019-2021) (can I use this? Licenced to TUM for reproduction in Computer Science lecture contexts only)

### Business Section

1. Understand
	- "Understand the problem and requirements of the user" (Engelschall)
	- Roles: #roles/manager [[Manager]] #roles/player [[Player]]
	- Context: Be specific and clear about what the players want
	
2. Ideate
	- Find a solution for the discovered problems and requirements
	- Roles: #roles/manager [[Manager]] #roles/designer [[Designer]]
	- Context: First brainstorming and idea collections to the solutions of the problems found in 1.
	
3. Explore
	- Get on a deeper level and explore your solutions, find alternatives, look for technologies that could be used
	- concretize your solutions
	- bring it on paper
	- Roles: #roles/manager [[Manager]] #roles/designer [[Designer]] #roles/artists [[Artist]] #roles/engineers [[Engineer]]
	- Context: everyone can collaborate and bring their ideas to the table, use mood boards etc. to explore the game's aesthetic, pin point what you want to create, define first dynamics and playgoals, play with your ideas
	- Input: Ideas
	- Output: [[Methods/Mood Boards]] , [[Reference Collection]], [[Collection]]
	- Related Tools: [[Storage Tools]] [[Digital Design Tools]]
	
4. Specify
	- "Specify the functionality and quality of the solution" (Engelschall)
	- Go into detail here
	- summary of the last steps
	- write it down
	- Roles: #roles/manager  [[Manager]] #roles/designer [[Designer]]
	- Context: Specify the mechanics and rules ("build your game on and around the mechanics and rules" (Totten?)), write down your core ideas and communicate it to the team
	- Input: Ideas and findings from the last steps
	- Output: [[Methods/Game Design Document]]? , [[Document]]
	- Related Tools: [[Storage Tools]] [[Communication Tools]]

### Development Section
5. Design
   - "design how to implement the solution in an orthogonal, adequate and sustainable way" (Engelschall)
   - important step before implementing
   - also designing the architecture of your project
   - Roles: #roles/manager [[Manager]] #roles/designer [[Designer]]
   - Context: Use the methods (method summary) we have gathered to get concrete designs for your level, find a way to implement the mechanics into your game, draw a map, connect the big picture to the smaller levels, find a storyline and implement it in your gameplay, remodel and refactor your ideas, use tools to get a good result
   - Input: Design Document, Drawings and Sketches from the last steps, mechanics, game plan, ...
   - Output: Refactored Game Design Document, Maps, [[Pacing Diagram]], [[Gym Scene]], More diagrams and graphs (like [[Methods/Molecule Diagram]]), [[Diagram]]
   - Related Tools: [[Digital Design Tools]], [[Storage Tools]], [[Communication Tools]]
     
6. Implement
   - Put your ideas into code
   - Make the solution feasible and implement it according to the requirements
   - One of the most crucial steps, takes a lot of time
   - Roles: #roles/engineers [[Engineer]] #role, s/manager [[Manager]]
   - Context: Make your level playable, transfer your ideas into code, transfer your mechanics into code, add art, tools and assets
   - Not yet playtesting
   - Input: Design Document, Timeline (plan with milestones etc.?), game plan, overall outputs from design step
   - Output: Code and playable level, prototype and finished model
   - Related Tools: [[Game Engines]], (sharing platform like Gitlab/Github)
   - Related Processes: [[Prototyping]]

7. Build
   - Package the solution and build it 
   - Roles: #roles/engineers 
   - Context: Make a playable demo that can be started from your choice of device
   - Input: Ready level
   - Output: Build
   - Related Tools: [[Game Engines]]
   
8. Verify
   - "Review and test the functional and non-functional aspects of the solution" (Engelschall)
   - Look back at the requirements and check if everything that should be implemented has been implemented
   - Roles: #roles/engineers  #roles/designer #roles/tester (?)
   - Context: First iteration endpoint because now you start to playtest your level and change stuff that needs doesn't work yet/ is not to your expectations
   - Here it deviates from Software Engineering Workflow because they don't roll back to design and implementing phase but first they go through the operation phase
   - Input: Built level or built game
   - Output: Document of bugs, errors etc., Feedback, maybe also decision if it can be operated or not
   - Related Tools: [[Game Engines]], End-Device, Feedback [[Document]]
   - Related Processes: [[Prototyping]] ?

### Operations Section
9. Deploy
   - "Ship and deploy the solution releases and their updates in an automated and repeatable way"
   - Ready to sell?
   - Roles: #roles/manager #roles/engineers 
   - Context: Publish Alpha/Beta version and make it accessible for players (with a way to update your game)
   - Input: Built and tested game/level
   - Output: The same as input
   - Related Tools: End-Device
     
10. Integrate
    - "Integrate the solution with its target environment"
    - Make sure it works on the device/in the environment it was deisgned for
    - Roles: #roles/manager #roles/engineers 
    - Context: Verify that it works on the devices you want to include
    - Input: Built and tested game/level
    - Output: Same but maybe some corrections to make it work in the desired environment
    
11. Operate
    - Run the solution in a secure environment, make sure it can run repeatedly and secure
    - Roles: #roles/manager #roles/engineers (but only System Administrators, not developers)
    - Context: Doesn't differ from classic software engineering
    - Input: The game
    - Output: Game that's running
      
12. Monitor
    - Constantly monitor the solution under run-time (Engelschall)
    - Become aware of errors and unpredicted difficulties
    - Roles: #roles/manager #roles/engineers (System administrators etc., not a development job)
    - Context: Find bugs, maybe also with the help of players and forums. Consistently monitor how your game works in the desired environment.
    - Input: The game
    - Output: Bug reports, don't change the game yet

13. Adapt: Back to business section so that you can learn from your mistakes and rebuild a better solution
    - Same with Game Development Process, this is the important iteration step so that you can improve your game and keep it up-to-date with multiple iterations
    - Your game / level will never be perfect so don't stop working on it

## Applicability

- Some aspects and steps relate to Game Development in general since games are also a product that needs to be shipped
- Not focusing on business here so the Integrating step has to be made but we focus on design, implementing and testing more
- Game development difference could be: First design, implementation and testing (lots of testing), then iterate back to design and after all these iterations start with the Operations section

### Pros and Cons

- Has been proved to be successful for many products
- Looks at the process from the business side as well
- Very top-down and abstract so it can be applied to various products
- good to compare it to the Game Development Workflow

Cons:
- Too abstract
- not enough iterations
- too much business in our case?
- doesn't consider the player (the outside receiver) as a role I think

## Related Processes

Next and previous processes

## Relevant Tools (?)
- [[Game Engines]]
- [[Digital Design Tools]]
- [[Digital Diagram Tools]]
- [[Storage Tools]]
- [[Communication Tools]]

## Relevant Literature

Software Engineering in der industriellen Praxis Vorlesung, Dr. Ralf S. Engelschall, http://seip.direct/#engelschall-SGX4-2FK4