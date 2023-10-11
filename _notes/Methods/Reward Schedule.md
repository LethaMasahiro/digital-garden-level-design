---
title: Reward Schedule
tags:
  - method
  - medium/text
  - process/designing
  - process/planning
  - roles/designer
  - used-by/designer
  - used-by/engineers
  - roles/player
  - tools/digital
  - tools/non-digital
aliases:
---

also known as: 

## Classification
- #method 
#medium 
#process 
#roles 
#used-by 
#tools 
...

## Intent

- Motivate players to continue playing and eagerly anticipate the game.
- Utilize rewards to maintain player interest and attention.
- Employ schedules to ensure rewards are distributed consistently.
- Strike a balance between the quantity of rewards (not too many or too few).
- Influence player behavior.

## Problem

- Need to sustain player interest.
- Encourage players to continue playing and explore the game world.

## Solution Approach

- Instead of randomly providing rewards, consider implementing a consistent pattern that makes players anticipate and look forward to rewards.
- It's not always about the size and impact of a reward but also about when the reward is received.

## Application

### Input

- An existing level (alternatively with an existing story structure).
- A plan outlining the rewards you intend to place in the level.

### Application

- There are two types of reward schedules that you can apply:
    
    - **Ratio Schedule**
        - *Fixed Ratio*: Rewards are provided after a fixed number of player actions or responses. For example, in Tetris, players are rewarded each time they fill a line.
            - Offers predictability and enables players to expect rewards, integrating them into their strategies.
        - *Variable Ratio*: Rewards are given after an unpredictable number of player actions or responses. For example, in Monster Hunter World, there is a random chance that a defeated monster drops a rare resource.
            - Generates excitement and serves as a stronger reward.
              
    - **Interval Schedule**
        - *Fixed Interval*: Rewards are provided after a predefined amount of time (e.g., in League of Legends, players receive bonus experience and in-game currency once per day for playing). Regardless of how many times the player completes an action within the interval, they receive the reward only once per interval.
        - *Variable Interval*: Rewards are given after an unpredictable amount of time. As with fixed interval rewards, players only receive the reward once per interval.
          
- Decide which schedule you would like to implement and plan your rewards accordingly.
- You can also mix these types based on your preference.
    

### Output

- A written plan on paper, in a markdown file, or any other [[Text]] format of your choice.
- A [[Document]].

### When to Use It

- When you want to incorporate rewards and plan them to better structure your level.
- When you want to keep players engaged with rewards.
- When you want to balance risks with rewards.

### Relevant Roles Using This Model

- #roles/designer [[Designer]] #used-by/designer
- #roles/player [[Player]]
- [[Engineer]] #used-by/engineers 

## Relevance in the Following Processes

- [[Game Development]] Design phase.
- [[Iterative Map Design]] and [[Gamespace Prototyping]] when thinking about where to put the rewards

## Applicability

- Useful to have a plan, especially in large levels where structured motivation is needed to keep players engaged.

### Pros and Cons

**Pros**:

- Provides structure and a plan.
- Effective when followed through and tested after implementation.
- Allows for mixing different types to achieve various player behaviors.

**Cons**:

- Requires a variety of reward types.
- Limited to four types, potentially restrictive.
- Need to consider different schedules for open-world, storyline-based, online, etc.
- Striking a balance between what's too obvious and what's too hard for players can be challenging.

## Relation with other Methods
- [[Behavior Diagram]]
- [[Lenses]] as they define the rewards for a player
- [[Pacing Diagram]]
- [[Symbols and Visual Language]] can be used in tandem to define a coherent look for the game

## Examples

- **Fixed Ratio Example**: In Mario Kart (1992), players are instantly rewarded with power-ups upon hitting one of the rotating dices
  
- **Variable Ratio Example**: Genshin Impact (2020) implemented a gatcha system called Wishes that drops rare characters and weapons. The drop rate depends on rarity of the item, increasing the player excitements when drawing a rare card.

- **Fixed Interval Example**: A daily bonus is given out in several games.

- **Variable Interval Example**: In a management game, an NPC that is difficult to handle could drop by randomly. Upon succeeding in managing the client, the player might receive a special bonus. There will only be one difficult client per interval.

## Relevant Tools

- [[Communication Tools]]
- [[Non-digital Design Tools]]
- [[Digital Art Tools]]

## Relevant Literature

[[Reward Schedules and when to use them]]

[[Totten 2019 - An Architectural Approach of Level Design]], p.261

[[The Use of Player-centered Positive Reinforcement]] to schedule in-game rewards increases enjoyment and performance in a serious game

[[Schedules of Reinforcement]]

[[The Benefits of playing Video Games]]
