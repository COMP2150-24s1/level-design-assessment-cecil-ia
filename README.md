[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Cecilia Tran
### Student number: 47878983

Word Count : 1529

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

In my initial layout for the level design, the map was set up in a way where it would be easy for new players to understand the basic setup of the game, and get used to the easier mechanics before it started to progress into a harder stage. Each level would bring a new mechanic / obstacle that the player would need to pass in order to progress, so by the time they reached the third level, they would know how to bypass each obstacle to reach the door. 

The first level would introduce acid, spitters, moving platforms and the gun weapon. This would give the player an opportunity to learn how to move around, use the weapons to defeat the spitter, and to figure out how to navigate the platforms. There would still be a risk which is the spitter and the acid.

The second level would introduce the staff weapon, checkpoints, chompers, spikes and disappearing platforms. By attempting to get through the second level, the player should be able to navigated all game mechanics to be able to complete the third level. 

![Introductory level 1](DocImages/Untitled167_20240407182656.png)

*Introductory level 1*

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

The general layout of the level designs was that it started off easy and relatively easy going, with the most dramatic section being the end of level three. The format of level one is relatively straightforward and small, as it is an introduction level and doesn’t need to be so complicated. 

As the player begins to figure out how the game works and what they need to be able to navigate each level, the game begins to become more intense after the first, with the third being the level with the most intensity as it is not only the most challenging level, but it contains more game mechanics compared to the other two. 

The third level contains more enemies for starters, which would make the game more dramatic for the player as there are higher risks of losing health. Furthermore, the variety of both moving platforms and fading platforms cluttered right before the final door would also create a sense of urgency for the player.

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

The main challenges in the game would be both the enemies, or the risk of falling into a danger zone after failing a jump. This can be seen especially in the last level, where there are more risky jumps and enemies scattered around compared to the previous two levels. 

The first level has low risk, as the acid puddles aren’t too difficult to navigate over, and the gun is close to the spawn point, which means that they can easily take out the spitter on the other side. The second level has an increased difficulty as there are fading platforms, and taking too long on them would risk falling into a spike pit. 

Compared to those two levels, the third level has the most risk, which makes it the most challenging. The addition of two health spawns placed before the start of the third level, as well as the spawn point, would aid the player in completing the level as it may be difficult to get through the entire game and complete the third level in one go.

Due to the layout of each stage and the obstacles planned for each one, the difficulty level and challenge would become more intense as the player progresses through the game. 

![Obstacle clutter in level 3](DocImages/Untitled167_20240407182729.jpeg)

*Obstacle clutter in level 3*

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

There are multiple opportunities for exploration in the game. The first is in the first level, where it is optional for the player to take out the spitter. In the second level, the player has an option to go through a passage to grab an additional heart, as well as additional ways to get back to the start of the level rather than having to go around the block again.

By adding variety in choices and opportunities into the level design, the game invites the player to take their own paths, and encourages map exploration.

![Alternate passage to collect heart in level 2](DocImages/Untitled167_20240407182719.jpeg)

*Alternate passage to collect heart in level 2*

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

The acid is located at the start, a few steps away from where the player starts the game. There are two puddles of acid right away, so that the players have a chance to understand the basic mechanics of the game.

![Place any alt text here](DocImages/Untitled167_20240407195458.png)

### 2.10. Weapon Pickup (Gun)

The gun pickup is located on the platform above the starting point, which makes it easy to access. This is so that the player can take out the enemy on the first level easily. 

![Place any alt text here](DocImages/Untitled167_20240407194225.png)

### 2.6. Moving Platforms

The first moving platforms are located on the first level, and are placed in a way that the player needs to use them in order to make it to the top floor of the level where the key is. It has been placed for the player to learn how to use them.

![Place any alt text here](DocImages/Untitled167_20240407194757.png)

### 2.9. Spitters

The first spitter is located on the first level as it is an easier boss to deal with, so the players can get used to using a gun to fight the enemies.

![Place any alt text here](DocImages/Untitled167_20240407202830.png)

### 2.5. Keys

The first key is located at the top of the first level, so at the end of that stage. It has been placed here to show the player which direction they need to run in.

![Place any alt text here](DocImages/Untitled167_20240407195333.png)

### 2.2. Checkpoints

There are two checkpoints in the game - The first checkpoint is located at the start of section two, and the second one is at the start of section three. This is to ensure that players won’t have to go back to the beginning of the game if they fail the next stages.

![Place any alt text here](DocImages/Untitled167_20240407202200.png)

### 2.11. Weapon Pickup (Staff)

The staff pickup is located at the start of the second level, right before the enemy encounter. This is because the number of enemies from then on will increase, so the pickup will make the game a bit easier for the player.

![Place any alt text here](DocImages/Untitled167_20240407202557.png)

### 2.3. Chompers

The first chomper is located at the start of the second level. It is placed on a flat platform so that the players have an opportunity to figure out how to defeat it to get through to the next level.

![Place any alt text here](DocImages/Untitled167_20240407202750.png)

### 2.8. Spikes

The spikes are located above the first spike encounter to warn the players that there are consequences if they don’t manage to pass this stage.

![Place any alt text here](DocImages/Untitled167_20240407200043.png)

### 2.7. Passthrough Platforms

The passthrough platforms first show up during the second level. It is the first more advanced obstacle that the player will need to pass to increase the difficulty.

![Place any alt text here](DocImages/Untitled167_20240407203143.png)

### 2.4. Health Pickups

The first health pickup is located near the end of the second level. It is located in a separate area near the key, so that the player has an option to pick it up, otherwise, they can ignore it. It was also placed here as the player may need it before heading into the third level. They are usually located after a dangerous encounter

![Place any alt text here](DocImages/Untitled167_20240407203323.png)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

I had planned out my map prior to attempting to recreating it in Unity. The beta design was quite simple, and I had figured that it wouldn’t be too difficult for a new player to run through the whole game quite easily.

![Beta design plan](DocImages/Untitled165.png)

*Beta design plan*

For example, the stages were originally set up so that the third stage would show up on top of stages one and two. When I started creating the levels, I thought that it would be more interesting to spread the levels out in a line so that the map would look a little bigger, and therefore more interesting. It would also look less compact. 

![Place any alt text here](DocImages/Untitled167_20240407201201.png)

*Level 3 setup change*

I also needed to add more moving platforms to level one as the original design didn’t have enough to allow the player to reach the next platform.

![Place any alt text here](DocImages/Untitled167_20240407201254.png)

*More moving platforms added to level 1*

Another change I made was at the beginning of the second stage. I had decided that because they hadn’t reached the second heart at that point yet, I would remove the spikes and let the player deal with just the chomper instead. 

However, as I was recreating the game in Unity, there were a lot of aspects that I decided to change just because it didn’t play out how I wanted in the beta design.

I also made the second level underground to add some more excitement to the game environment, and so that the player wouldn’t feel too boring and repetitive. 

Of course, I wasn’t able to play test the game due to major technical issues, such as Ellen not being able to move. (I have discussed this with someone already, and it might be due to my computer). The game does not commit to GitHub either, so the marker will unfortunately not be able to test the game either. 

Because of this, there is likely a lot of error within my game design as I don’t know factors like how high and far Ellen can jump, and how the mobs move around, all of which can affect how the game turns out. This would ultimately affect the gameplay, and the difficulty level for the player as there are so many uncertain variables to go by. 

Overall, I think the game would be relatively easy to play if it had worked. The flow of the game might be too simple as there are no major challenges that would actually make the player think. It is too straightforward, which might be more suitable for younger players who wouldn’t be able to figure out map puzzles, but definitely not difficult enough for the marker who would actually be playing the game. 


## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.

### Tool Used: None
