---
title: Game Design Document
---


also known as: 

## Classification
- #method 
- #medium/text 
- #roles/writer #roles/designer #roles/engineers #roles/artists #roles/manager 
- #used-by/designer #roles/writer #used-by/engineers #used-by/artist #used-by/manager 
- #tools/non-digital #tools/digital 

## Intent
- mapping out your ideas of the game and sort them
- explore the WHY behind your game and always have access to it so you don't get lost in it
- Guidance through the game development process
- map design decisions

## Problem

### General
- With every project, it's important to document changes and descisions somewhere to always get back on track
- Communicating within a team becomes easier if the vision is written down somewhere
- Documentation needed especially for Waterfall development methods

### Specific
- Sometimes you lose the WHY after working on a game project for so long
- Where do you start? Do you need a guide that guides you through the process of designing a game?
- The entire team has to be on the same path and talk about the same things.
- You might forget what you wanted to work on next
- The more complex the game is, the harder it is to keep the concept in your head
- Publishers expect you to present some form of documentation together with your game (https://www.codecks.io/blog/2020/writing-modern-game-design-documents/#why-use-game-design-documents)

## Solution Approach

### General

### Specific
- Create a Game Design document where your concept, the reason for the game and a step-by-step guide on how to plan the game is written down
- All about making design decisions
- Always think about "what needs to be remembered and what needs to be communicated" (Schell)
- There are many different kinds of documents specified for different roles, there's not THE game design document

## Application

### Input
- first, you have the decisions you want to write down and communicate
- Blank document that has to be filled

### Application

-  General guidelines for your documentation (https://www.codecks.io/blog/2020/writing-modern-game-design-documents/#why-use-game-design-documents):
	- Keep it minimal
	- Documents become outdated quickly, so in case the document doesn't catch up, let the game be your document. Use it as a reference rather than as a separate document that gets forgotten quickly.
	- Use it as part of your project management. Put all mechanics and designs along other daily bugs in your project management tool to integrate them in the process rather than handling them as separate tools. 
	  
- A guideline of how a game design document can look like excluding marketing and business sections (https://dev.to/garrett/a-game-design-document-gdd-tutorial-that-will-save-you-time-and-energy-238n):
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

- Here is another guideline of a Game Design Document (https://www.gamedeveloper.com/business/how-to-write-a-game-design-document):
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
	6. Art style: How does your game look like? Her you can also refer to [[Reference Collection]] and [[Mood Boards]]
	7. Music and Sounds: Often overlooked, it is important to define Music and Sound to describe the atmosphere of your game.
	8. Technical Description: Describe the platform and the tools you're using to develop the game. For a detailed Technical Description, create a Technical Design document instead.
	9. Marketing and Funding: How do you plan on funding your project? How do you advertise it? This is important even before starting your game development. This also includes:
		1. The demographics: Which group of people do you target with your game?
		2. Platform & Monetization: How do you release your game on each platform?
		3. Localization: Which languages do you support?
	10. Other ideas: Add anything that was missing in the previous sections.
	    
- getting more specific: Depending on the role and the section in which you need the document, decide on which type of document you need (Schell)
  
	- Design:
	  
		- ###### Game Design Overview:
		   Written by [[Designer]] for [[Manager]] so that the latter understands roughly what the game is about, can be used as a basis for publishing contracts
		  
		- ###### Story Overview:
		  Written by [[Designer]] to [[Writer]] to describe the important elements of the story (setting, milestones etc. ) to a person who is contracted out of the team and just focuses on writing the detailed story
		  
		- ###### Detailed Design Document:
		  Written from [[Designer]] to [[Designer]], see the guide above
		  
	- Art: 
	  
		- ###### Art Bible: #roles/artists #used-by/artist 
		  Written from [[Artist]] to [[Artist]], provides consistency and guidelines on the artwork of the game
		  
		- ###### Concept Art Overview: #roles/artists #used-by/designer 
		  Written by [[Artist]] to [[Designer]], set of images that show how the game will look and feel like in the context of the game design 
		  
	- Engineering: 
	  
		- ###### Technical Design Document: #roles/engineers #used-by/engineers 
		  Written by [[Engineer]] to [[Engineer]], technical details that are recorded in a document to establish consistency over the whole engineering team, important to have the system architected and documented
		  
		- ###### Pipeline Overview: #roles/engineers #used-by/artist 
		  Written from [[Engineer]] to [[Artist]], how to integrate the assets into the game
		  
		- ###### System Limitations: #roles/engineers #used-by/designer #used-by/artist 
		  Written by [[Engineer]] to [[Designer]] and [[Artist]], state the limitations of the systems (e.g. number of polygons in one frame)
		  
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
- A Game Design Document, [[Document]]
- Or other documents depending on which ones you want to use

### When to use it
- Communicating with your team, updating new team members and establishing a certain consistency throughout the development process
- Prepare for publishing contracts
- Guide your team through the development
- Write down ideas before starting the development process

### Relevant Roles using this model
- #roles/designer [[Designer]] #used-by/designer 
- #roles/artists  [[Artist]] #used-by/artist 
- #roles/manager [[Manager]] #used-by/manager 
- #roles/engineers [[Engineer]] #used-by/engineers 
- #roles/player [[Player]] #used-by/player 
- #roles/writer [[Writer]] #used-by/writer 

## Relevancy in the following processes
- [[Game Development]]
- [[Prototyping]] ??

## Applicability
- For a strict waterfall model, it's good to document every step and declare which steps to do next
- But for Agile Development (the current trend of game development) critical voices get loud. People claim that Game Design Documents are not needed anymore since it's obsolete and no one updates them so they become outdated very quickly (reference from one of the websites)
- It is also said that Game Design Documents are a practice from the past (https://www.gamedeveloper.com/business/how-to-write-a-game-design-document).
- Using a lot of images and making the document visual might improve its readability

### Pros and Cons

Pros:
- Serves as a guidance and maintains the values and most important aspects of the game throughout the whole development process
- Transparency within the team since every member's knowledge of the game is written down and passed to other members
- Defines the scope of your game
- Basis of negotiation for business contracts
- Supports waterfall model

Cons: 
- Synchronizing the Game Design Documents with the project is hard since the production is faster than the documentation process
- Often too long to read and exhausting to maintain
- A good idea on paper does not have to be a good idea in practice and can foster false confidence towards the actual product
- Might be an outdated approach for some and doesn't align well with Agile developing because of the continuous changes

## Relation with other Methods

The following can all be part of the created document:

- [[Reference Collection]]
- [[Mood Boards]]
- [[Reward Schedule]]
- [[Drawing a Map]]
- [[Behavior Diagram]]
- [[Pacing Diagram]]
- [[Pillars, Goals and Features]]

## Examples
- The original [[Diablo Game Design Document]]
- The detailed [[Prince of Persia Documentation and Design Bible]]
- The [[Doom Bible (GDD)]]

## Relevant Tools
- An open and collaborative digital tool like Google Docs (link) or Nuclino for a more visual approach
- [[Digital Collection Tools]]

## Relevant Literature


https://dev.to/garrett/a-game-design-document-gdd-tutorial-that-will-save-you-time-and-energy-238n

https://www.gamedeveloper.com/business/how-to-write-a-game-design-document

https://www.codecks.io/blog/2020/writing-modern-game-design-documents/#why-use-game-design-documents

https://www.nuclino.com/articles/write-game-design-document

LD -In Pursuit of better level design (https://docs.google.com/document/d/1fAlf2MwEFTwePwzbP3try1H0aYa9kpVBHPBkyIq-caY/edit)

Schell - A book of lenses

https://www.gamedesigning.org/learn/game-design-document/