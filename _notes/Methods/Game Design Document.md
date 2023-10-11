---
title: Game Design Document
tags:
  - method
  - medium/text
  - roles/writer
  - roles/designer
  - roles/engineers
  - roles/manager
  - roles/artists
  - used-by/designer
  - used-by/writer
  - used-by/engineers
  - used-by/artist
  - used-by/manager
  - tools/non-digital
  - tools/digital
aliases:
---


also known as: 

## Classification
- #method 
- #medium/text 
- #roles/writer #roles/designer #roles/engineers #roles/artists #roles/manager 
- #used-by/designer #roles/writer #used-by/engineers #used-by/artist #used-by/manager 
- #tools/non-digital #tools/digital 

## Intent

- Mapping out your game ideas and organizing them.
- Exploring the WHY behind your game and maintaining access to it to avoid losing sight of the vision.
- Providing guidance throughout the game development process.
- Making informed design decisions.

## Problem

### General

- In every project, it's vital to document changes and decisions to stay on course.
- Effective team communication becomes easier when the game's vision is documented.
- Documentation is particularly crucial for Waterfall development methods.

### Specific

- Over time, it's easy to lose sight of the WHY behind a game project.
- Knowing where to start can be challenging. Do you need a guide to lead you through the game design process?
- Ensuring the entire team is aligned and discussing the same concepts is crucial.
- Ideas can be forgotten, causing uncertainty about what to work on next.
- As games become more complex, maintaining the entire concept in your head becomes increasingly challenging.
- Publishers expect you to present some form of documentation together with your game (_Source: [link](https://www.codecks.io/blog/2020/writing-modern-game-design-documents/#why-use-game-design-documents)_)

## Solution Approach

- Create a Game Design Document that includes your concept, the rationale behind the game, and a step-by-step guide for planning the game.
- Focus on making design decisions.
- Always consider "what needs to be remembered and what needs to be communicated" ([[Schell 2014 - A Book of Lenses]]).
- Note that there are various types of documents tailored to different roles; there isn't a single standard Game Design Document.

## Application

### Input

- Decisions you want to document and communicate.
- A blank document to be filled.

### Application

-  General guidelines for your documentation ([Why use Game Design Documents](https://www.codecks.io/blog/2020/writing-modern-game-design-documents/#why-use-game-design-documents)):
	- Keep it minimal
	- Documents become outdated quickly, so in case the document doesn't catch up, let the game be your document. Use it as a reference rather than as a separate document that gets forgotten quickly.
	- Use it as part of your project management. Put all mechanics and designs along other daily bugs in your project management tool to integrate them in the process rather than handling them as separate tools. 
	  
- A guideline of how a game design document can look like excluding marketing and business sections ([A GDD Tutorial](https://dev.to/garrett/a-game-design-document-gdd-tutorial-that-will-save-you-time-and-energy-238n)):
	1. First Page: 
		- Start with the name of the game
		- Add your team's name
	2. The pages after: 
		- Elevator pitch: Write down how your game can be explained in one sentence
		- Story brief: One paragraph that summarises the story of your game
		- Gameplay Features: Describe how the players play the game. Also include game controls.
		- Levels: How many levels do you have? What are the names of the levels? Write down a short description of each level. 
		- Menu Screens: Describe each menu screen and what is needed in these screens.
		- Art Assets: Which art assets are needed?
		- Sound Assets: Which sounds are needed?
	- General Rules:
		- Use a document editing tool like Google Drive that can also be shared and collaborated on with others
		- Instead of putting images in the document, link them and put them in a separate folder
		- Save the different versions of your document instead of overwriting them

- Here is another guideline of a Game Design Document ([How to write a Game Design Document](https://www.gamedeveloper.com/business/how-to-write-a-game-design-document)):
	1. Project Description: Briefly summarise what the game is about.
	2. Characters: Describe your characters before your describe the plot. Add characteristics to the characters and describe how they look.
	3. Story: Describe the Story behind your game and guide the reader through the important events happening. You can also write about the genre and recurring themes of your story.
	4. Story Progression: How will the player experience this story, how will they be guided through the story? [[Pacing Diagram]] might come in handy here.
	5. Gameplay: Describe what the gameplay will be like in the following sections
		1. Goals: Why is the player playing the game?
		2. User Skills: Which skills are needed? You can include hard skills and soft skills. Even intuitive skills like tapping on the screen are important to note down.
		3. Game mechanics: What will the player be able to do and what are their limitations? Write down each mechanic in detail
		4. Items and Power-ups: Which items can be collected and interacted with? Do they give a buff or have a negative impact impact on the player?
		5. Progression and challenge: How will the difficulty increase, which tools help the player catch up to the difficulty, how will the game difficulty feel after a certain time?
		6. Losing: What are the losing conditions, how do you treat losing? Where are the save points, how much does the player lose upon a game over screen?
	6. Art style: How does your game look like? Here you can also refer to [[Reference Collection]] and [[Mood Boards]]
	7. Music and Sounds: Often overlooked, it is important to define Music and Sound to describe the atmosphere of your game.
	8. Technical Description: Describe the platform and the tools you're using to develop the game. For a detailed Technical Description, create a Technical Design document instead.
	9. Marketing and Funding: How do you plan on funding your project? How do you advertise it? This is important even before starting your game development. This also includes:
		1. The demographics: Which group of people do you target with your game?
		2. Platform & Monetization: How do you release your game on each platform?
		3. Localization: Which languages do you support?
	10. Other ideas: Add anything that was missing in the previous sections.
	    
- Getting more specific: Depending on the role and the section in which you need the document, decide on which type of document you need (_Source: [[Schell 2014 - A Book of Lenses]]_)
  
	- Design:
	  
		- ###### Game Design Overview:
		   Written by [[Designer]] for [[Manager]] so that the latter understands roughly what the game is about, can be used as a basis for publishing contracts
		  
		- ###### Story Overview:
		  Written by [[Designer]] to [[Writer]] to describe the important elements of the story (setting, milestones etc. ) to a person who is contracted out of the team and just focuses on writing the detailed story
		  
		- ###### Detailed Design Document:
		  Written from [[Designer]] to [[Designer]], see the guide above
		  
	- Art: 
	  
		- ###### Art Bible: #roles/artists #used-by/artist 
		  Written from [[Roles/Artist]] to [[Roles/Artist]], provides consistency and guidelines on the artwork of the game
		  
		- ###### Concept Art Overview: #roles/artists #used-by/designer 
		  Written by [[Roles/Artist]] to [[Designer]], set of images that show how the game will look and feel like in the context of the game design 
		  
	- Engineering: 
	  
		- ###### Technical Design Document: #roles/engineers #used-by/engineers 
		  Written by [[Engineer]] to [[Engineer]], technical details that are recorded in a document to establish consistency over the whole engineering team, important to have the system architected and documented
		  
		- ###### Pipeline Overview: #roles/engineers #used-by/artist 
		  Written from [[Engineer]] to [[Roles/Artist]], how to integrate the assets into the game
		  
		- ###### System Limitations: #roles/engineers #used-by/designer #used-by/artist 
		  Written by [[Engineer]] to [[Designer]] and [[Roles/Artist]], state the limitations of the systems (e.g. number of polygons in one frame)
		  
	- Management: 
	  
		- ###### Game Budget: #roles/manager #used-by/manager 
		  Written by [[Manager]] to [[Manager]], usually a spreadsheet that calculates the costs of a game before it is developed, mostly collaborated with externals to come up with the costs
		  
		- ###### Project Schedules: #roles/manager 
		  Written by [[Manager]] to everyone else, all the tasks and milestones are documented on this list with their deadline, can be translated to a program designated for project schedules (e.g. Jira)
		  
	- Writing: 
	  
		- ###### Story Bible: #roles/writer #used-by/writer
		  Written by [[Writer]] to [[Writer]], defines what is possible and what is not possible within the game's world, other roles can contribute to it as well since they have a different perspective on the possibility of certain features (e.g. an element might be too complicated to code in the eyes of the engineers)
		  
		- ###### Script: #roles/writer #used-by/designer 
		  Written by [[Writer]] to [[Designer]], writing down the explicit dialogues and actions by NPCs, and dialogue decisions by the player, created after the Story Overview
		  
		- ###### Game Tutorial and Manual: #roles/writer #used-by/player
		  Written by [[Writer]] to [[Player]], teaches the player how to play the game, can be in-game tutorials, handbooks or websites
		  
	- Player: 
	  
		- ###### Game Walkthrough: #roles/player #used-by/player 
		  Written by [[Player]] to [[Player]], self-made guides through the game that are published through social media and websites, often written when it's already too late to change the game since it has already been published

### Output

- A Game Design Document
- Or other [[Document]]s  with text, depending on which ones you want to use

### When to use it

- For effective team communication, updating new team members, and ensuring consistency throughout development.
- When preparing for publishing contracts.
- To guide your team through the development process.
- To document ideas before commencing development.

### Relevant Roles using this model

- #roles/designer [[Designer]] #used-by/designer 
- #roles/artists  [[Roles/Artist]] #used-by/artist 
- #roles/manager [[Manager]] #used-by/manager 
- #roles/engineers [[Engineer]] #used-by/engineers 
- #roles/player [[Player]] #used-by/player 
- #roles/writer [[Writer]] #used-by/writer 

## Relevancy in the following processes

- [[Game Development]], implemented and used in all process steps
- [[Combat Design]] should be documented in a Game Design Documented
- All maps created in [[Iterative Map Design]] can be stored along with the Game Design Document

## Applicability

- In a strict waterfall model, it's beneficial to document each step and declare the next steps to follow.
- For Agile Development (the prevailing trend in game development), some argue that Game Design Documents are no longer necessary as they can quickly become outdated when not regularly updated (reference from one of the websites).
- Some consider Game Design Documents to be a practice from the past ([link]([https://www.gamedeveloper.com/business/how-to-write-a-game-design-document](https://www.gamedeveloper.com/business/how-to-write-a-game-design-document))).
- Others believe that Game Design Documents lack standardaziation and formalization [[A Systematic Review of Game Design Methods and Tools]].
- Improving document readability by incorporating images and visual elements might be advantageous.

### Pros and Cons

**Pros**:
- Provides guidance and maintains the game's core values throughout the development process.
- Enhances transparency within the team by documenting each member's knowledge of the game.
- Defines the game's scope.
- Serves as a basis for negotiating business contracts.
- Supports the waterfall model.

**Cons**: 
- Synchronizing Game Design Documents with the project can be challenging, as production often outpaces the documentation process.
- Documents are often lengthy and demanding to maintain.
- A concept that looks good on paper may not work well in practice and can lead to unfounded confidence in the final product.
- Might be considered outdated by some and may not align seamlessly with Agile development due to ongoing changes.

## Relation with other Methods

The following can all be part of the created document (this is not a complete list):

- [[Reference Collection]]
- [[Mood Boards]]
- [[Reward Schedule]]
- [[Drawing a Map]]
- [[Behavior Diagram]]
- [[Pacing Diagram]]
- [[Pillars, Goals and Features]]
- [[Critical Path Analysis]]
- [[Behavior Diagram]]
- [[Symbols and Visual Language]]

## Examples
- The original [[Diablo Game Design Document]] 
- The detailed [[Prince of Persia Design Bible]]
- The [[Doom Bible (GDD)]]

## Relevant Tools

- An open and collaborative digital tool like Google Docs (link) or Nuclino for a more visual approach
- [[Digital Collection Tools]]

## Relevant Literature


[[GDD Tutorial]]

[[How to write a Game Design Document]]

[[Why use Game Design Documents]]

[[Write Game Design Document]]

[[Game Design Document Website]]

[[TychoBolt (K., Alex) 2020 - In Pursuit of Better Levels]]

[[Schell 2014 - A Book of Lenses]]

[[A Systematic Review of Game Design Methods and Tools]]

