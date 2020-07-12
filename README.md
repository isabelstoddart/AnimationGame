# AnimationGame

This is an interactive game made by me and two group members for an undergrad graphics class at UT Austin.

For this project I created the Enemy class, the EnemyCollection class, and the stars in the background.

To run the program first download Processing, then download all of the files and open the AnimationGame.pde file inside of the AnimationGame folder and click Run! Be sure to click the AnimationGame.pde inside of the folder and be sure the folder is named AnimationGame or the file will not run.

You can download processing here -> https://processing.org/download/

The Game:
- In the Welcome Screen, you can simply choose 1 player or 2 players
- player shoots the enemies. The enemies will come down the screen at different speed
  depending on the difficult level the player is inputted initially.


Interactivity:
  - Please see the end of this file for the default controller layouts
  - Something interesting: feel free to resize the project. The pixels will stretch to any size
  
  - Moving with the arrow pad
  - Firing with a, and b button
  - Pausing with the start button
  - Selecting with the start button


GUI Interface:
  - Keeping scores for both players and HighScore
  - Players current difficult level
  - selection between two players
  - Enemies disappear when shot
  

Win/Loss Rule:
  -	If a player(s) destroyed all enemies, the player(s) win the stage, and move to the next
  -	If the enemies come down to the base, the player(s) lose the stage at the cost of a life
  -	If the player(s) run out of lives, they lose and the game ends taking them back to the
	main menu
	

Controller Layouts:

When 1 player:

Button:     Keyboard:
ArrowPad <- arrows
A		 <- z
B		 <- x
Start    <- Enter

When 2 players:

Player1:
Button:     Keyboard:
ArrowPad <- wasd
A		 <- f
B		 <- g
Start    <- t

Player2:
Button:     Keyboard:
ArrowPad <- arrows
A		 <- Alt		(Please avoid, alt may be faulty because of its use in modern OS)
B		 <- Ctrl
Start    <- Enter
