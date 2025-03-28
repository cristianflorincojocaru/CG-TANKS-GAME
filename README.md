# Computer Graphics - TANKS! - UNITE BOSTON 2015


### DESCRIPTION :
**"TANKS!"** is a **3D**, **2-player shooter** game created in **Unity**, following one of its tutorials. It was originally recorded at **Unite Boston 2015**. It uses **simple game mechanics**, integrating **world** and **screen space UI**, as well as **game architecture** and **audio mixing**. 

You and a friend will battle using **one keyboard** over multiple rounds to determine which tank is the strongest.



## TECHNOLOGIES USED
The **main technologies** used for this project / game are :

**UNITY** - The game engine used to develop the game.

**C#** - The **programming** language used for scripting and game logic.



## GAME CONTROLS

|          **ACTION**        	    |  **BUTTON** |             **DESCRIPTION**          	|
|:------------------------------: |:---------:	|:-----------------------------------:	|
| Player **no. 1** - SHOOT     	  |   SPACE   	|     Fire the **'Player 1'** tank's gun    |
| Player **no. 1** : HORIZONTAL (+) 	|    **d**   	| Move the **'Player 1'** tank to the right |
| Player **no. 1** : HORIZONTAL (-) 	|    **a**   	|  Move the **'Player 1'** tank to the left	|
|  Player **no. 1** : VERTICAL (+)  	|    **w**   	|    Move the **'Player 1'** tank forward  	|
|  Player **no. 1** : VERTICAL (-)  	|     **s**   |     Move the **'Player 1'** tank back    	|
| **( - )**                                  |   **( - )**        |          **( - )**                   |
| Player **no. 2** - SHOOT     	  |   ENTER   	|   Fire the *'Player 2'* tank's gun     	|
| Player **no. 2** : HORIZONTAL (+) 	|   RIGHT   	| Move the *'Player 2'* tank to the right	|
| Player **no. 2** : HORIZONTAL (-) 	|    LEFT   	|  Move the *'Player 2'* tank to the left	|
|  Player **no. 2** : VERTICAL (+)  	|     UP    	|    Move the *'Player 2'* tank forward  	|
|  Player **no. 2** : VERTICAL (-)  	|    DOWN   	|    Move the *'Player 2'* tank back     	|


## GAME FEATURES
### Features added based on the tutorial :
### 1. 2 players, 1 keyboard for shared gameplay
> **EXPLANATION** : It’s not the most appealing name ( *if you know, you know* ), but anyway, as the title suggests, **2 players** have to share **a keyboard** to actually play the game. The **game controls** are explained in the repository.

### 2. PLAYER vs. PLAYER competitive action
> **EXPLANATION** : The players / tanks can move around a spacious map, filled with obstacles and objects that can either **hinder them** or **help them** in **eliminating the opponent** or **being eliminated by the opponent**.

### 3. Win by reaching 5 rounds first
> **EXPLANATION** : For one player to officially **WIN** the game, they must defeat their opponent in **5 individual rounds**. To be honest, I couldn’t decide if it should be **2 rounds** or **100 rounds** to win.

### 4. Round notifications displayed during gameplay
> **EXPLANATION** : At the beginning of the game, after each round, whether won or in the case of a draw, messages are displayed on the screen to inform the players about the progress of the game.

### 5. Leaderboard appears after each round
> **EXPLANATION** : The scoreboard appears after each round to notify the players of the **game’s score**, whether they want to **retreat** or perhaps make a **legendary comeback**, all the way until the score reaches **5**.

### 6. Complete tank control for both players
> **EXPLANATION** : The players have **full control** over the tanks.

### 7. Health bars displayed around each tank
> **EXPLANATION** : **Health bars**, specifically **circles**, are located around the tanks to help players keep track of how much health their tank has left.

### 8. Adjustable shooting power for 'strategic' attacks
> **EXPLANATION** : Projectile shots are quite interesting ; you must carefully **time your shots** to ensure the projectile hits the opponent with **enough power**. If not, there’s a chance the projectile could **damage you instead**, or worse, you might leave yourself exposed if your shot misses and goes over the opponent.

### 9. Explosive effects for 'impactful' battles
> **EXPLANATION** : The projectiles explode, ***BOOOOM***, either next to you or causing you to explode. Your opponent will really **enjoy the animation**, so try to make sure you explode them before they do it to you !

### 10. Damage based on 'explosion proximity' to the tank
> **EXPLANATION** : Projectiles **deal damage** depending on their **power** and the **location** where they land. They can damage both you (even if they’re your own) and your opponent, and vice versa. Be careful with your aim, as in some cases, you might even cause a **DRAW**.

### 11. Diverse sound effects for an 'immersive' experience
> **EXPLANATION** : The tanks have a sound of **idling**, and a **functional engine** sound when **moving**. The **projectiles** also have their **own sound effects**, and there’s a **background music** track (*which I personally find a bit annoying*) to make the game more **enjoyable** and **"realistic."**


### Features added by ME, after completing the tutorial :
### 1. TIMER - keep an eye on the clock
> **EXPLANATION** : It represents the **time** you have to **COMPLETE** the game, normally **45 seconds**. If the time runs out and neither of the two players has dealt **enough damage** to **WIN** the round or **eliminate** the opponent, it is considered a **DRAW**. The ***score will remain the same***, and ***a new round*** will start within the game, **aimed at eliminating the opponent**.

### 2. PAUSE button - what if one of you needs an urgent break ?
> **EXPLANATION** : Implemented for **key moments**, **unexpected breaks**, or simply for ***fun**, it helps **both** players take a break if needed.




## CONTRIBUTIONS 
Project created by **Cristian Florin Cojocaru** (**CSE.2** - **University of Craiova / Faculty of Automatics, Computer Science and Electronics**). Contributions are welcome ! If you have suggestions for improving the code or documentation, please submit a pull request.


## LICENSE
This project is licensed under the [MIT License](LICENSE).
