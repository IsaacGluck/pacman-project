Pacman-Replicated Game
=====================
Isaac Gluck

To Run
------------

Download just the jar here: [Pacman Jar](https://www.dropbox.com/sh/cu2sphjr6zkodre/AAAKezgyYh8GlGgLz5H8Ay-ca/pacman.jar?dl=0)

Double-click the pacman.jar file to play the game!


More levels can be added but they must fill the following requirements:

1. The data must be represented by a 19 by 29 grid seperated by commas (no spaces)

2. There must be 11's at all the corners

3. 1's and 11's are treated as fruits, 21 is a powerup, 2 is a wall, 0 is free space

4. Save the file in the levels folder ("exampleLevel.txt") and add to the array `levels` in Board.java

5. To recompile the new level(s) into a jar file, use the terminal to navigate to the *pacman-project* directory

6. Once in the directory run the following command:
```
jar cfm pacman.jar manifest.txt *.java *.class users.txt images/*.png levels/*.txt
```

Introduction
------------
This pacman game is a classic pacman game!
When you open the game, there are several options for the main menu:

* If you are playing this game for the first time and want to register as a player, enter your desired username and password and click **Register** button. Then using the data, log in to the game.

* If you want to play as a guest, click **Guest Play**. Your information (your highscore) *will not be stored*.

* If you want to resume your game, enter your username and password and click **Login**. Your previous level and high score will be shown

**IMPORTANT**

For your game to be safely saved, you *must* click **Main Menu** at the end of your game. It also takes a few seconds to record your data, so do not quit the java window right away.

How to Play
-----------
1. The main rule is simple: eat as many fruits as you can before you die.

2. When you eat fruits, they give you 1 point (good). If a ghost eats you, you lose a life (not good).

3. If you eat a super fruit, you turn invincible for a several seconds (better). While you are in super pacman mode, you may eat monsters to gain extra points (best).

4. After your super mode is over, the monsters you ate will regenerate in the screen and all monsters will once again ruthlessly chase you.



