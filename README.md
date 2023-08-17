# BattleShipGame

Below is a Java program for a Battleship game that can be played in the console. The objective is to sink three battleships named Justin, Osiel, and Ivan using the least number of guesses:

1BattleshipGame: This class acts as the game manager, orchestrating the entire gameplay experience. It handles battleship setup, provides instructions, collects and validates user guesses, evaluates their accuracy, and concludes the game when all battleships are successfully sunk.

2Battleship: This class defines the battleship objects, each having a unique name and a collection of location cells. It includes a method called "checkYourself" that assesses a user's guess and determines whether it results in a hit, miss, or the ship being sunk.

3GameHelper: This utility class is responsible for managing user interactions, battleship placement, and diverse in-game computations. It generates randomized starting positions for battleships, facilitates coordinate conversion, and validates the suitability of chosen positions.



