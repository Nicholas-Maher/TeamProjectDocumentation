# 25/09/2026

## Meeting
We are going to use Markdown for documents. Tomas created a guide with Markdown shortcuts and spoke about it.
Our collective progress will be written under the Progress heading of the Journal.

## Progress
Created basic template for the game using Thomas is Late code by removing existing features such as two player and split screen elements just leaving basic template for testing our main character. Came up with a concept for the playable character its weapon, clothes where main inspiration came from the movie WolfWalkers. Attempt was madded to create animation to simulate character movement. Concluded some additional research about most used device screen resolution in recent games, that showed us more than 70% of steam environment player base utilize two major resolutions 1080p and 1440p. What we will do with that information its on the next session agenda.



# 29/09/2026 

## Meeting
We chatted about the previous session. We looked at what we did during the previous session. We talked about the concept Clo designed for the playable character, decided on our approach to doing meeting minutes and recording our progress since the last meeting, and decided what tasks each of us would need to do the next day. Tomas will look into template menus. Patrick will look at Packman AI and see what can be adapted into our game.

## Progress
During this stage we mainly focused on cleaning up and preparing existing template for our game, and review what needed to be changed before moving forward with creation of our game. We also made improvements to the characters look and how behaves utilizing sprite sheet. Additional research was done including player movement mechanics and allowed us to explore different approaches like player slide changing directions or slowing down before stop. 


# 02/10/2026

## Meeting
This meeting was most important we focused on creating concrete plan for upcoming weeks and we split tasks to achieve player movement, enemies, level environment, and character visual look. We separate some features between need to be done, must have, and maybe we implement if we have additional time for development.

## Progress
This week, we continued working on the game and made progress with its overall design. We looked into how to implement sprites and how sprite sheets work, which helped us better understand how to use them in our game. We also updated the .gitignore file to prevent unnecessary files and folders from being included in the project. As a group, we explored different enemy designs, each with its own interesting features. We also fixed the background and started planning the level layout.


# 06/10/2026

## Meeting
We talk about assets and focused what size we can use with minimal code changes and how much can reuse of them before we need to make art ourselves. Decision was made that character has to have special ability and some enemies has to feed that ability to make character stronger for upcoming stronger enemies. We had discussion about level manager and his effect on our game environment.

## Progress
This week, we started implementing the sprite sheet into the game and researched ways to make the player move and stop more naturally. We added velocity, acceleration, and deceleration variables to the player character, allowing the player to speed up gradually and slide to a stop. We also worked on the camera so it follows the player horizontally while keeping them centred vertically. After some adjustments, we managed to get it working as intended. Alongside this, we created several enemies that can benefit the player and help improve their abilities.


# 09/10/2026

## Meeting
Have discussion how about we extend game levels, their length and difficulty. Overview some aspects related to character animations reusing sprite sheet, get agreement for the enemies required to the game. At the moment there will be 4  enemies and their types as a static  which is ready for combat but not benefit player, second enemy has feature to increase player ability charge bar, third enemy wil gives player some point that later can upgrade characters ability, and last one will be a boss with some features.

## Progress
This week, we continued working on the sprite sheet code to make sure the character animations works correctly in gameplay. We also started planning how to expand the game by adding more levels once the first level is complete. This involved looking at how the code could be updated to support additional levels in the future.

We also worked on defining the four enemy types and their roles in the game. The first enemy will be a standard enemy designed for combat, while the second will help increase the player's ability charge bar. The third enemy will reward the player with points that can later be used to upgrade their abilities. Finally, we planned a boss enemy with its own special features.


# 13/10/2026

## Meeting
Had small discussion about progress we done, review some features that we able to finish in time, and excluded some of them from future implementation. Had a chat how enemies should behave inside the level, how they should behave if character approach them, and how tey move if obstacles in their path.

## Progress
Fixed some issues with the template, including changes to the character which now has health, created new class entity which responsible for enemies creation and started plan for creation additional class for enemies behavior inside level environment. Additional progress whit drawings how we perceive visually levels and obstacles inside them.


# 20/10/2026

## Meeting
Chat about creating documents community plan and project management plan, we start research about templates for those documents. Starting discussing about character main ability, trying describe our vision how would look like, what effect will have on character or the enemies including visual look of environment of the level


## Progress
Multiple fix including code which makes transition between animations and different states of the player, additionally health bar was missing after merging between branches inside git hub so fix was done to review code and find missing parts. 


# 23/10/2026

## Meeting
Review our plan for next what has to be done, so to speak bear minimum we have to have character health and strength for attack also start building special ability, enemies and their behavior, some progression  to make character stronger, need some work for the level itself because at the moment is very plain.  

## Progress