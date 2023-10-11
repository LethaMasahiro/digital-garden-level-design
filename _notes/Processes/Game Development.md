---
title: Game Development
tags:
  - process
aliases:
  - Agile Game Development
---

also known as: Agile Game Development

## Intent

- Develop a complete game (a level is just part of the game).
- Understand the game development process, its complexity, and the importance of simplifying it.
- Recognize that game development is a work-intensive process and utilize repeatable game objects and textures to reduce the need for constant recreation of art assets ([[Totten 2019 - An Architectural Approach of Level Design]], p.90-91).

## Problem

- Every game starts with an idea, but how do you organize a team to implement those ideas into a unique and enjoyable game?
- Level design is just a small part of the whole game development process, so it's essential to understand what game development encompasses to successfully connect levels to the entire game.
- Two approaches exist: the waterfall approach and an agile approach. This process describes an agile approach that aligns with agile product management principles, iterating continuously to refine the scope.

## Process Steps: Seven Stages of Game Development

### 1. Planning (Concept phase)

- Define the game idea.
- Address key questions: 2D or 3D? Core mechanics? Aesthetic? Story? Target audience? Platform?
- Input: Ideas and motivation for creating a game.
- Application: Collaborate as a team to decide the game's concept.
- Output: Written or visualized game ideas, development process plan, key decisions.
- Roles: #roles/manager [[Manager]], #roles/designer [[Designer]].
- Relevant Tools: [[Communication Tools]], [[Digital Collection Tools]], [[Digital Diagram Tools]], [[Non-digital Design Tools]].
- Relevant Methods: [[High Concept]], [[Lenses]], [[Pillars, Goals and Features]]

### 2. Pre-Production

- Define the game's scope.
- Focus on game design with the application of various methods.
- Develop the game concept in detail and align story, art, and technical aspects.
- Input: The concept from the planning phase.
- Application: Collaboratively design a detailed game concept that seamlessly transitions into the production phase.
- Output: Documentation summarizing all decisions and plans for application in the production phase.
- Roles: Everyone, including #roles/manager [[Manager]], #roles/designer [[Designer]], #roles/engineers [[Engineer]], #roles/artists [[Artist]], #roles/writer [[Writer]].
- Relevant Tools: [[Communication Tools]], [[Digital Art Tools]], [[Digital Diagram Tools]], [[Non-digital Design Tools]].
- Relevant Methods: [[Methods/High Concept]], [[Reference Collection]], [[Mood Boards]], [[Pacing Diagram]], [[Drawing a Map|Drawing a Map]], [[Molecule Diagram]], [[Paper Prototype]], [[Proximity Diagram]], [[Game Design Document]], and more.

### 3. Production

- Implement the concept, design ideas, and decisions.
- The project takes shape in this phase.
- This phase consumes the most time.
- Input: Materials from previous stages.
- Application: Produce all necessary game components for an engaging player experience.
- Output: The game, after several iterations.
- Roles: #roles/designer [[Designer]], #roles/artists [[Artist]], #roles/engineers [[Engineer]], #roles/writer [[Writer]].
- Relevant Tools: [[Computational Tools]], [[Game Engines]], [[Digital Art Tools]], [[Communication Tools]], [[Digital Collection Tools]].
- Relevant Methods: [[Massing]], [[Nintendo Power Method]], [[Gym Scene]].

### 4. Testing

- Test all elements developed so far.
- **Iterative Game Design**: Each iteration involves playtesting, evaluation, and revisions.
- Agile game development iterates continuously, reducing bugs and changes (see iterative game design image). 
  ![](PlaytestingPyramid.png)
   _(Source: [[Game Design Workshop.pdf]])_
- Input: Game segments or the entire game for testing.
- Application: Play and test the game comprehensively, focusing on different aspects such as mechanics, pacing, and the integration of artwork and animations. Consider inspiration from [Software Testing](https://kaner.com/pdfs/ETatQAI.pdf) for guidance. Release alpha versions for player feedback.
- Output: An evaluation of the game, potentially documented.
- Roles: #roles/tester [[Tester]], #roles/player [[Player]].
- Relevant Tools: [[Game Engines]], [[Communication Tools]], [[Digital Collection Tools]].
- Relevant Methods: [[Game Design Document]], [[Critical Path Analysis]], [[Nintendo Power Method]], [[Gym Scene]].

### 5. Pre-Launch

- Market and advertise the game.
- Generate hype to attract players on the release date.
- Roles: #roles/manager [[Manager]].

### 6. Launch

- Release the game.
- Ensure all bugs are fixed, and the game offers an enjoyable experience before launch.
- Be prepared for unexpected issues, such as server problems for online modes.
- Roles: #roles/player [[Player]].

### 7. Post-Production

- Ongoing work after launch.
- Address post-launch bugs.
- Plan future updates and additional content to keep players engaged.
- Consider future sequels.
- Player feedback is vital.
- Roles: #roles/manager [[Manager]], #roles/designer [[Designer]], #roles/engineers [[Engineer]], #roles/artists [[Artist]], #roles/tester [[Tester]], #roles/player [[Player]].

## Applicability

- Suits agile development well. For a waterfall approach see this blog: https://www.gamedeveloper.com/business/waterfall-game-development-done-right
- Leans on the [[Software Engineering Workflow]] and can therefore manage small and big teams. 
- Only serves as an introduction to agile game development. The topic is too big to fit it in one page. See https://www.gamedeveloper.com/production/agile-game-development-with-scrum-teams for a more in-depth look at game development with scrum teams.

### Pros and Cons

**Pros**:
- Short iteration circles that uncover problems early
- Efficient game development
- Steps are easy to follow

**Cons**:
- Falls short in more rigid structures that might prefer a waterfall model
- Is only in theory. Every game development looks different and unique.
- Might focus too much on the production phase and doesn't put emphasis on the management actions.

## Related Processes

- Closely related to [[Software Engineering Workflow]] because game development is just another form of software development.
- Includes smaller processes like [[Combat Design]], [[Iterative Map Design]] and [[Gamespace Prototyping]] in the pre-production and production phase.


## Relevant Literature

[[Stages of Game Development]]

[Game Design Chapter 7: Gameplay](https://d1wqtxts1xzle7.cloudfront.net/5386859/gameplay-libre.pdf?1390841267=&response-content-disposition=inline%3B+filename%3DAndrew_Rollings_and_Ernest_Adams_on_game.pdf&Expires=1694617224&Signature=WPGiMLOG367QoDfiTEzSMqKhirnPrc6ZHZ3Ba~TAqdpHLtuhVdGaKacBZKCBwCCm6ASCkz2hlQ8mPtTUSSoSejq~xVHyf4gX2~RMlfcQ4FE9b70lM0jB5pnc9oCEB-01ZVhaRt-hPecm4hkMZAkAp7L9LfJ~vWynw4RRplna0TXE6zz9zocoLIgme7eC9uA0a3KFxvZtuYsvlfuCd-vhfk2lkrX~P9xuogWMVeTjJ~d6YJSV3Iyma~jVrNf0fylfbdnLmab-Lve05AyQz2yIntjldqENN9UbCPdZUy2Z7sw0KtjYaZowAVXV2kL5ffA1qQ2Rq1ZeNB6CEPt8aMuY9Q__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)

[[Game Design Workshop]]

