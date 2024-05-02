[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=14589322&assignment_repo_type=AssignmentRepo)

:warning: Everything between << >> needs to be replaced (remove << >> after replacing)

# << Project Title >>
## CS110 Final Project  << Semester, Year >>

## Team Members

Alex Wang

***

## Project Description
The core gameplay revolves around defending a designated area from waves of enemies by strategically placing turrets along their path. Each turret costs 200 gold to purchase, and players earn gold by defeating enemies. Additionally, players receive one gold for each enemy they kill and earn an additional 50 gold at the end of each round.

With multiple waves of enemies, each wave presents a greater challenge than the last, keeping players engaged and requiring them to continuously refine their strategies. Moreover, the inclusion of unique enemy types, such as planes, adds variety and excitement to the gameplay experience.
<< Give an overview of your project >>

***    

## GUI Design
The GUI design of the game is intuitive and user-friendly, with all essential elements conveniently displayed on the screen. Players can easily access information about their current level, health, and available gold, ensuring they stay informed and engaged throughout the game.



### Initial Design

![initial gui](assets/gui.jpg)

### Final Design

![final gui](assets/finalgui.jpg)

## Program Design
The program is structured to efficiently handle game logic, user input, and graphical rendering using the Pygame library in Python. Key features of the program design include:

Modular Structure: The code is organized into separate modules for enemies, world management, turrets, buttons, and constants, promoting code reusability and maintainability.

Asset Loading: Images, sounds, and level data are loaded from external files, allowing for easy customization and expansion of the game content.

Game Loop: The main game loop efficiently updates and draws game elements, ensuring smooth gameplay and responsive user interaction.

User Interface: The GUI design is implemented using Pygame's drawing functions, providing players with a visually appealing and intuitive interface to interact with the game.

Event Handling: Pygame events are processed to handle user input, such as mouse clicks and window closures, ensuring smooth and responsive gameplay.
### Features

1. << Feature 1 >>
Fast forward 
2. << Feature 2 >>
Upgrading Towers
3. << Feature 3 >>
Multiple Waves
4. << Feature 4 >>
Custom bugs as enemies 
5. << Feature 5 >>
Shooting sound effects
### Classes
Enemy, World, Turret, Button
- << You should have a list of each of your classes with a description >>
Enemy: Represents enemy entities in the game.
Responsible for handling enemy movement, health, and damage.

World: Represents the game world, including the map layout and level progression.
Responsible for processing level data, spawning enemies, and managing game progression.

Turret: Reresents defensive towers that the player can place on the map.
Responsible for attacking enemies within its range, upgrading, and managing turret behavior.

Button: Represents clickable buttons within the game interface.
Responsible for handling button interactions and visual representation.
## ATP


Test Case 1:
a. Test Description: Verify that the game starts correctly when the "Begin" button is clicked.
b. Test Steps:

Launch the game.
Click on the "Begin" button.
c. Expected Outcome: The game should start, and enemies should begin to spawn according to the predefined pattern.

Test Case 2:
a. Test Description: Confirm that turrets can be placed on valid grass tiles when the player attempts to place them.
b. Test Steps:

Launch the game.
Click on the "Buy Turret" button.
Move the cursor over a grass tile.
Left-click to place the turret.
c. Expected Outcome: A turret should be successfully placed on the selected grass tile, and the player's currency should decrease by the cost of the turret.

Test Case 3:
a. Test Description: Validate that turrets can be upgraded when the player has sufficient funds.
b. Test Steps:

Launch the game.
Place a turret on the game grid.
Select the placed turret.
Click on the "Upgrade Turret" button.
c. Expected Outcome: The selected turret should be upgraded to the next level, and the player's currency should decrease by the cost of the upgrade.

Test Case 4:
a. Test Description: Ensure that the game ends with a win when all levels are completed successfully.
b. Test Steps:

Launch the game.
Successfully complete all levels by defeating all enemy waves.
c. Expected Outcome: The game should display a "YOU WIN!" message, indicating that the player has won.

Test Case 5:
a. Test Description: Verify that the game ends with a loss when the player's health reaches zero.
b. Test Steps:

Launch the game.
Allow enemies to reach the end of the path and deplete the player's health to zero.
c. Expected Outcome: The game should display a "GAME OVER" message, indicating that the player has lost.
