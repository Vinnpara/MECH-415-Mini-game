# MECH-415-Mini-game
2D Mini game capable of multiplayer over network communication. Supports single and 2 players. The objective in 2 player mode is to either collect more coins than your opponet before a timer runs out or sink their ship by firing torpedos.

The game enviornment(including collisions between the ship and torpedos), the battleships, torpedos, obstacles, and coins are in classes of their own. Network communication is handled through various functions.

The Ship class creates the players ship and controls the movement, the torpedo class does the same as the Ship class for the torpedos. The Coin class creates the coins for the players to collect, The Island creates the obstacles. The World class creates the game enviornment by loading a background and creating the objects using the aforementioned classes. The World class also includes functions to manage collisions between the players ships and the obstacles, coins, and torpedos. 


