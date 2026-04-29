# Project - Return of the Scarecrow

I will be continuing from my previous game from CS1. This game will be a top-down game stylized close to the style of the 1998 PC game, "Clue: Murder at Boddy Mansion". The game will run on Godot using GDScript rather than Python. While gameplay, functionality, and coding are essential to the project to functon as a whole, sound design will be my focal point. I will be using open source sounds for certain aspects, or placeholders for demos, and I will be recording my own sounds as well. The sounds will also be directional and proximity based on the sprites to the player character. This dynamic sound design will allow the player to use surround sound headphones to avoid a premature meeting with the scarecrow. I will also be adding pop-up windows, different scenes, and a mini game aspect (safe cracking or something like that).

##Worldbuilding:
The previous game ends with the player refueling an old truck and driving through a gate to escape the cornfield and the malevolent "scarecrow" that was pursuing the player. This is a direct sequel that will take place as the player drives the same old truck to their secluded house. As the player feels relieved to have finally escaped and return to the safety of their home, they realize something is wrong. As the player enters the house, they will notice straw and corn husks greeting them in their house. The player will have to carefully sneak around the house while avoiding the scarecrow, collecting clues, and finally defeating their obsessive enemy.


https://www.youtube.com/watch?v=dq0uYzGq2ok #This is just a youtube video of gameplay of the reference game.

## Milestone 1

My first milestone is to have a basic foundation of the game created. This will include nodes and folders created and at least the starting area created. I will also have the instructions for the game implimented.

### Current Progress

I have the a blue background set, a player character that has animations, and the scarecrow sprite. Basic scripts have been written. This has taken hours of research and testing to get this far but I feel like I do not have a lot done so far.

### Challenges

I have never used Godot, and this is my second semester of coding experience, so this program is entirely new to me. This has proved to be a bit of a challenge, but the script language is very similar to Python, so that is reassuring. 

I am having trouble uploading the complete file to gitlab so it is able to be ran. Will be asking prof. Mielko for assistance 3/2 in class.

### Future Directions

I would like to have more functionality to the game added. I would like to have more of the house layout set up and more movement options to the player character. As far as the house goes, I would like to have a new area for the house set up next time.


## Milestone 2

My second milestone has the game 90% complete desing wise. House is nearly completeley set up, just needs more detail. Player can adjust speed of walk now. Interconnecting scripts added between scenes. Currently there is no way to "win" yet. 

### Current Progress

There is now a Main Menu and instructions in the spawn area. I Have added a counter that activates every interaction between the player and the scarecrow. Once the counter reaches 5 hits, the game will revert to main menu and reset inventory. The player can interact with the world for a message and with items to pick the items up. Once picked up the items will leave the floor and be in the player inventory. The player can check their inventory by pressing "e" and a message will display every item in your inventory. The scarecrow follows a set path in the house

### Challenges

Getting the multiple scenes to interact and "remember" the inventory was challenging but fun. Working through the code was difficult with adding new functions and having them call each other but finally having the functions not crash the game was quite rewarding each time! 

### Future Directions

Other than polishing and finishing the "back yard", I mainly need to add sounds. 
That is the bulk of Milestone 3. I saved sound for the end because I wanted to get the majority of the new 
material and hard work finished before goofing around with the sound studio software.


## Final Submission

### Overview

This game acts as a demo for my idea of a stealth escape game, similar to 'Outlast' but not as spooky (you cannot attack and must hide or outrun enemies). The demo game follows the main player character, from my previous project 'scary maze game'. This game features a GUI and a top-down view of the character. Story-wise the character returns home after escaping from the scary maze. Although when returning home, the player realizes the scarecrow has followed you! You must be sneaky and find the key to escape the house!
### Tutorial

CONTROLS: 
'wasd' or "up, down, left, right" for movement.
hold 'tab' for sprint
'e' to open your inventory
'q' to interact with the environment or to pick up collectible
'esc' to quit/end game

The game takes movement functions from 'wasd' or up, down, left, right, keys. The player makes noise that attracts the scarecrow if you get too close. You must get out of the line of sight of the scarecrow and stop making noies for it to stop chasing you. The 'tab' button acts as a sprint, but sprinting makes more noise. The player can find a pair of sneaking boots to make less noise and not attract the scarecrow. You have 3 hit points essentially. If the scarecrow makes contact with you a third time, the game is over.

The main objective of the game is to escape to the backyard well where you can hide from the scarecrow. In order to get into the backyard, the player needs to find a key in the basement. This requires hiding and evading from the scarecrow at least two times. Once the key is retrieved, the player can enter the backyard and then jump into the well to end the game.

### Installation Instructions

https://github.com/NMcBain/github.io this link will open a GitHub repository
https://nmcbain.github.io/github.io/ this link will directly open the web portfolio on the repository. There is a link to releases and you will open the .exe file, download the 92MB file and the game will run off that file.

### Citation, Sources, and References

https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html 
#GDScript reference

https://www.youtube.com/watch?v=dq0uYzGq2ok 
#youtube video of Clue that I am referencing.

https://opengameart.org/content/classic-hero 
#hero textues

https://craftpix.net/ 
#other open source textures

https://kira.art/en-US/
#Krita editing software for manipulating textures and creating animations.

https://www.videolan.org/
#VCL media editor for converting mp4a to mp3 files

https://www.audacityteam.org/
#audacity for editing and manipulating sounds

https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html 
#godot script reference

https://docs.godotengine.org/en/stable/tutorials/scripting/nodes_and_scene_instances.html 
#godot nodes reference

https://ikoiku.itch.io/16-x-16-pixel-art-character-scarecrow 
#scarecrow textures

https://www.youtube.com/watch?v=NNnuXie3xVU&t=887s 
#video reference for top-down game creation
