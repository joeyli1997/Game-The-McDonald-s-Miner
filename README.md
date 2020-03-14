# Game-The-McDonald-s-Miner

![pic1](/images/menu.png)

### 1. Primary Purpose:
In the project, a program named “The McDonald’s Miner” is developed, which is a personal computer game. By developing this program, our group members realize basic game-development and get more familiar about C++. 


### 2. Introduction
- 2.1 Interfaces Introduction:

The game contains two scenes: the main menu scene and the level scene. In the main menu scene, there are two buttons: “START” and “SETTING”. By clicking the “START” button, a level-selection board would come out, which prompts the player to select the difficulty (easy, medium or hard). After level-selection, there comes the levels’ scene, which will be introduced later. By clicking the “SETTING” button, a setting interface will be displayed, which allows the player to turn on/off the background music, and check the game instruction. 

When the player enters the levels’ scene, the BGM would be changed. There are actually three levels’ scenes, each of which is a representation of certain difficulty. In each level, the player can click the “PAUSE” button to pause the game; when the game is paused, the player can continue the game or return to the menu by clicking corresponding buttons. Besides, the information about current level is shown on the top of the level, including the goal, currently gained calories, time left, and current number of level. 

- 2.2 Information about the Game: 

The idea of “The McDonald’s miner” originates from the classical game “The Gold Miner”. On the lower part of the interface, there is a panel including all the objects (French-fries, hamburgers, cola, box, mice). Above the panel, the Donald McDonald (also called “miner” in later text) is standing there with a dangling claw in his hand. The player can click anywhere on the screen to release the claw and catch the objects. Each object has its specific weight and calories. The heavier the object is, the slower it is being dragged. For each level, there is a demand for total calories and time limit; if the player gets enough calories within the time, he can pass that level; otherwise he will fail. The detailed information for the catchable objects are listed below: 

a. Hamburger: heavy to catch but rich in calorie; 

b. Cola: less heavy; less rich in calorie;

c. French-fries: very light; not much calorie contained;

d. Box: very light; contains an unknown amount of calorie;

e. Mouse: heavy; no calorie contained at all;

Besides, the player is provided with a bomb in each level; the bomb can remove the object under dragging whenever the player wants, in order to save some time. Notice that player has only one bomb for each level, so he has to be cautious when using it. 
When each level finishes, no matter whether the player wins or not, it would go back to the menu; if the player wants, he can restart the game with different difficulty.

![pic2](/images/gameinterface.png)
