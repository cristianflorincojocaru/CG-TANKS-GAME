# Computer Graphics - TANKS! - UNITE BOSTON 2015


### DESCRIPTION :
**"TANKS!"** is a **3D**, **2-player shooter** game created in **Unity**, following one of its tutorials. It was originally recorded at **Unite Boston 2015**. It uses **simple game mechanics**, integrating **world** and **screen space UI**, as well as **game architecture** and **audio mixing**. 

You and a friend will battle using **one keyboard** over multiple rounds to determine which tank is the strongest.

> [!IMPORTANT]
> This project is based on the **original tutorial** for the game **"TANKS!"**, specifically the **first version of the game**, which was presented at **Unite Boston 2015**.
>
> The tutorial was available until **April 1st, 2025**. Starting from that date, **Unity** released a [**new tutorial**](https://learn.unity.com/course/tanks-make-a-battle-game-for-web-and-mobile) based on the same game, but with some changes that make the newly published project on their website feel like a **"new game"**.

> [!NOTE]
> The **core idea remains the same**, but the **implementation** is **slightly different**.



## TECHNOLOGIES USED
The **main technologies** used for this project / game are :

**UNITY** - The game engine used to develop the game.

**C#** - The **programming** language used for scripting and game logic.



## GAME CONTROLS

|          **ACTION**        	        |  **BUTTON** |                **DESCRIPTION**          	|
|:------------------------------:     |:---------:	|:-----------------------------------:	    |
| Player **no. 1** - SHOOT     	      |   SPACE   	|     Fire the **'Player 1'** tank's gun    |
| Player **no. 1** : HORIZONTAL (+) 	|    **d**   	| Move the **'Player 1'** tank to the right |
| Player **no. 1** : HORIZONTAL (-) 	|    **a**   	|  Move the **'Player 1'** tank to the left	|
|  Player **no. 1** : VERTICAL (+)  	|    **w**   	|    Move the **'Player 1'** tank forward  	|
|  Player **no. 1** : VERTICAL (-)  	|     **s**   |     Move the **'Player 1'** tank back    	|
|          **( - )**                  |   **( - )** |          **( - )**                        |
| Player **no. 2** - SHOOT     	      |   ENTER     |   Fire the *'Player 2'* tank's gun       	|
| Player **no. 2** : HORIZONTAL (+) 	|   RIGHT   	| Move the *'Player 2'* tank to the right	  |
| Player **no. 2** : HORIZONTAL (-) 	|    LEFT   	|  Move the *'Player 2'* tank to the left  	|
|  Player **no. 2** : VERTICAL (+)  	|     UP    	|    Move the *'Player 2'* tank forward   	|
|  Player **no. 2** : VERTICAL (-)  	|    DOWN   	|    Move the *'Player 2'* tank back      	|


## GAME FEATURES
### Throughout the tutorial, we've developed quite a few **game features**, such as :
- **2 players, 1 keyboard for shared gameplay :** Two players share a *single keyboard* to play the game, with the controls explained in the repository.

- **Player vs. Player competitive action :** The players, controlling tanks, navigate a spacious map filled with obstacles and objects that either hinder or help in *eliminating the opponent* or *avoiding being eliminated*.

- **Win by reaching 5 rounds first :** To win the game, one player must defeat the opponent in *five individual rounds*, with the exact number of rounds being flexible (e.g., between 2 and 100).

- **Round notifications displayed during gameplay :** After each round, whether won or drawn, *messages are shown on the screen* to inform the players about the game’s progress.

- **Leaderboard appears after each round :** The *leaderboard is displayed after each round* to show the current score, giving players a chance to strategize for a comeback or decide whether to retreat.

- **Complete tank control for both players :** Both players have *full control* over their respective tanks during gameplay.

- **Health bars displayed around each tank :** Each tank has a *visible health bar* in the form of a circle, allowing players to track how much health they have remaining.

- **Adjustable shooting power for 'strategic' attacks :** Players must carefully time their shots to ensure they hit the opponent with enough power, as *underpowered shots* can damage the shooter instead, or leave them *vulnerable* if the shot misses.

- **Explosive effects for 'impactful' battles :** Projectiles explode on impact, creating *dramatic effects*. Players should aim to explode their opponent before getting caught in their own blast.

- **Damage based on 'explosion proximity' to the tank :** Projectiles deal varying amounts of damage depending on their power and where they land, with the *possibility of damaging both players*, even their own tanks.

- **Diverse sound effects for an 'immersive' experience :** The tanks have *engine and idle sounds when moving*, while projectiles have their own effects. *Background music* is also included to enhance the overall experience, though it may be a bit annoying to some.


### In addition to the features mentioned earlier, which were implemented based on the tutorial, I personally added **new functionalities** to leave **my mark** on this project. These include :
- **Timer - keep an eye on the clock :** The timer represents the time you have to complete the game, typically set to *45 seconds*. If the time runs out and neither player has dealt enough damage to win the round or eliminate the opponent, the *round is considered a draw*. The score remains the same, and *a new round will start*, focused on eliminating the opponent.

- **Pause button - what if one of you needs an urgent break ? :** The pause button is implemented for *key moments*, unexpected breaks, or *simply for fun*, allowing both players to take a break if needed without interrupting the flow of the game.



## TESTING METHODS
If you want to play the game and test the final project, you can download the **4 archives** named ***"BUILD1 / 2 / 3 / 4"*** from the **'GAMEBUILD'** folder. After extracting the files from the initial archives, **place everything in a separate folder** for better file organization. Then, simply access ***"TANKS!.exe"*** and you can play endlessly with your friend. 
- **Minimum requirements** – **130 MB** of free space for download.

If you'd like to see the process behind the scenes, you're invited to download the **3 archives** ( *ASSETS, PACKAGES & PROJECTSETTINGS* ) from the **'PROGRAM FILES'** folder, which contain the original files behind the creation of the project. With these, you can make modifications to the project I have already completed, as you wish.

> [!NOTE]
> Even though some folders contain **multiple archives**, they have been split this way to upload the complete project to **GitHub** ( *with a file size limit of 25 MB* ). For example, the *'ASSETS'* folder contains 5 archives. If you download the files according to my folder structure, meaning all the files from *'ASSETS'* should be placed in the parent ***'ASSETS' directory***, the game / project will **run properly**.
>
> The same applies to the ready-to-play ***".exe" files***—although there are multiple *"BUILD"* archives, if they are all placed under a single parent folder, the game can be launched with a single click.



## ABOUT THE GAME FILES
> [!IMPORTANT]
> The modifications I made – ***the timer and the pause button*** – are found in the main file, which is powerful for the entire game, **"GameManager.cs"**. The rest of the files remain **standard**, as per the tutorial.

The rest of the files, as per the tutorial, are :

- ***"CameraControl.cs"*** – controls the camera to follow the two players.

- ***"TankManager.cs"*** – the **powerful file** for **global settings** ( *for both players* ), which is harder to work with compared to ***"GameManager.cs"***.

- ***"ShellExplosion.cs"*** & ***"UIDirectionControl.cs"*** – handle the **explosion effects** and **UI direction control**.

- ***"TankHealth.cs"***, ***"TankMovement.cs"***, & ***"TankShooting.cs"*** – deal with everything related to the tank, as their names suggest.


## CONTRIBUTIONS 
Project created by **Cristian Florin Cojocaru** (**CSE.2** - **University of Craiova / Faculty of Automatics, Computer Science and Electronics**). Contributions are welcome ! If you have suggestions for improving the code or documentation, please submit a pull request.


## LICENSE
This project is licensed under the [MIT License](LICENSE).
