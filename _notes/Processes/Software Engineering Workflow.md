---
title: Software Engineering Workflow
tags:
  - process
aliases:
---

also known as: 

## Classification
#process 

## Intent

- Develop software through a simple workflow, creating value for a company.
- Recognize that software engineering is an ongoing cycle rather than a one-time task.

## Problem

### General

- When starting software development, it's essential to understand the initial steps and how to increase efficiency.
- Concentrating on the development process, especially in designing, planning, and developing phases, is crucial.

### Specific

- Games are products and can benefit from classic software engineering practices.
- The goal is to see the game from beginning to end.
- Understanding the roles, inputs, outputs, and their interactions in each step is essential.

## Process Steps

![Software Engineering Workflow](assets/softwareengineeringworkflow.png) _Software Engineering Workflow by Ralf Engelschall (2019-2021) (used under license to TUM for reproduction in Computer Science lecture contexts only)_

### Business Section

1. **Understand**
    
    - "Understand the problem and requirements of the user" (Engelschall).
    - Roles: #roles/manager [[Manager]], #roles/player [[Player]].
    - Context: Be specific and clear about what the players want.
      
2. **Ideate**
    
    - Find a solution for the discovered problems and requirements.
    - Roles: #roles/manager [[Manager]], #roles/designer [[Designer]].
    - Context: Begin with brainstorming and idea collections to address the problems found in step 1.
      
3. **Explore**
    
    - Delve deeper into your solutions, find alternatives, and explore potential technologies.
    - Concretize your solutions and bring them to life.
    - Roles: #roles/manager [[Manager]], #roles/designer [[Designer]], #roles/artists [[Artist]], #roles/engineers [[Engineer]].
    - Context: Collaborate to bring ideas to the table, use mood boards, define aesthetics, play dynamics, and refine ideas.
    - Input: Ideas.
    - Output: [[Methods/Mood Boards]], [[Reference Collection]], [[Collection]].
    - Related Tools: [[Digital Collection Tools]], [[Digital Art Tools]].
      
4. **Specify**
    
    - "Specify the functionality and quality of the solution" (Engelschall).
    - Go into detail.
    - Summarize the previous steps.
    - Write it down.
    - Roles: #roles/manager [[Manager]], #roles/designer [[Designer]].
    - Context: Specify mechanics and rules, communicate core ideas to the team.
    - Input: Ideas and findings from the previous steps.
    - Output: [[Game Design Document]]?, [[Document]].
    - Related Tools: [[Digital Collection Tools]], [[Communication Tools]].

### Development Section

5. **Design**
    
    - "Design how to implement the solution in an orthogonal, adequate, and sustainable way" (Engelschall).
    - A crucial step before implementation, including designing the project's architecture.
    - Roles: #roles/manager [[Manager]], #roles/designer [[Designer]].
    - Context: Use methods gathered to create concrete designs for the level, map out mechanics, integrate aesthetics, and plan gameplay.
    - Input: Design Document, Drawings and Sketches from previous steps, mechanics, game plan, etc.
    - Output: Refined Game Design Document, Maps, [[Pacing Diagram]], [[Gym Scene]], and other relevant diagrams and graphs.
    - Related Tools: [[Digital Art Tools]], [[Digital Collection Tools]], [[Communication Tools]].
      
6. **Implement**
    
    - Translate ideas into code.
    - Make the solution feasible and implement it according to requirements.
    - One of the most crucial steps, time-consuming.
    - Roles: #roles/engineers [[Engineer]], #roles/manager [[Manager]].
    - Context: Make the level playable, translate mechanics into code, add art, tools, and assets.
    - Input: Design Document, Timeline, game plan, outputs from the design step.
    - Output: Code, playable level, prototype, and finished model.
    - Related Tools: [[Game Engines]], sharing platforms like GitLab/GitHub.
    - Related Processes: [[Gamespace Prototyping]].
      
7. **Build**
    
    - Package the solution and build it.
    - Roles: #roles/engineers
    - Context: Create a playable demo that can be started from various devices.
    - Input: Ready level.
    - Output: Build.
    - Related Tools: [[Game Engines]].
      
8. **Verify**
    
    - "Review and test the functional and non-functional aspects of the solution" (Engelschall).
    - Check if everything that should be implemented has been implemented.
    - Roles: #roles/engineers, #roles/designer, #roles/tester 
    - Context: Start playtesting and make necessary adjustments.
    - Deviates from the Software Engineering Workflow, as it doesn't roll back to the design and implementation phases.
    - Input: Built level or built game.
    - Output: Document of bugs, errors, feedback, and decisions on operability.
    - Related Tools: [[Game Engines]], end devices, Feedback [[Document]].
    - Related Processes: [[Gamespace Prototyping]]
    - 

### Operations Section

9. **Deploy**
    
    - "Ship and deploy the solution releases and their updates in an automated and repeatable way."
    - Is the solution ready for distribution?
    - Roles: #roles/manager, #roles/engineers.
    - Context: Publish Alpha/Beta versions and make them accessible to players, with a system for updating the game.
    - Input: Built and tested game/level.
    - Output: Same as input.
    - Related Tools: End-Device.
      
10. **Integrate**
    
    - "Integrate the solution with its target environment."
    - Ensure it functions on the intended devices or within the desired environment.
    - Roles: #roles/manager, #roles/engineers.
    - Context: Verify that it works on the designated devices.
    - Input: Built and tested game/level.
    - Output: Same, with potential adjustments to make it compatible with the target environment.
      
11. **Operate**
    
    - Run the solution in a secure environment, ensuring it can operate reliably and securely.
    - Roles: #roles/manager, #roles/engineers (specifically System Administrators, not developers).
    - Context: This phase aligns with classic software engineering practices.
    - Input: The game.
    - Output: A functioning game running in a secure environment.
      
12. **Monitor**
    
    - Constantly monitor the solution during runtime (Engelschall).
    - Detect errors and unforeseen difficulties.
    - Roles: #roles/manager, #roles/engineers (System administrators, etc., not a development role).
    - Context: Identify and report bugs, potentially with player and forum contributions. Continuously monitor how the game functions in the intended environment.
    - Input: The game.
    - Output: Bug reports; avoid altering the game at this stage.
      
13. **Adapt**
    
    - Return to the business section to learn from mistakes and build a better solution.
    - Similar to the Game Development Process, this iteration step is crucial for game improvement through multiple iterations.
    - Your game or level will never be perfect, so continuous improvement is essential.

## Applicability

- Some aspects and steps relate to Game Development in general, as games are also products that need to be shipped.
- While the integration step remains important, the primary focus is on design, implementation, and extensive testing.
- The difference in Game Development could be: First design, implementation, and extensive testing (including iterations), then revisiting the design, and finally, after multiple iterations, beginning with the Operations section.

### Pros and Cons

**Pros**:

- Proven successful for many products.
- Provides a comprehensive view from a business perspective.
- Highly abstract, making it applicable to various products.
- Useful for comparing it to the Game Development Workflow.

**Cons**:

- Abstract nature may pose difficulties in practical application.
- Insufficient emphasis on iterations.
- Potentially too business-oriented for Game Development.
- Lacks consideration of the player as a role in the process.

## Related Processes

[[Game Development]] in parallel

## Relevant Tools
- [[Game Engines]]
- [[Digital Art Tools]]
- [[Digital Diagram Tools]]
- [[Digital Collection Tools]]
- [[Communication Tools]]

## Relevant Literature

Software Engineering in der industriellen Praxis Vorlesung, Dr. Ralf S. Engelschall, http://seip.direct/#engelschall-SGX4-2FK4