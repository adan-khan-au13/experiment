# Snakes And Ladder Application
A python based application which works on CLI to function like the coventional snake and ladder game.
  
## Contents
* Snake and Ladder Application
* Contents
* Technologies
* About Code
* How to Use
* Methods Defined

## Technologies
Project is created using:
* Python: 3.8.6
* Flake8 (for liniting)
* Visual Studio Code IDE

## About Code
The application has been coded in python language using OOPS principle having objects and methods running with some user provided data.

## How To Use
* Open and run the code in any python IDE.
* Provide the user inputs like snakes' details, ladders, detail and players' names.
* Now just simply follow the commands in terminal and the game will go on smoothly until one player wins the game.

## Methods Defined
* start_game()
* roll_a_dice()
* check_ladder()
* check_snake()
* move_calculator()
* check_win()

## Working Details
* The program stores the position of ladders and snakes in a dictionary and the player names and their position in game in a nested list.
* When the dice is rolled, the dice value is added to the old position of player.
* The new position is checked in the snakes and ladders dictionaries; and if found then the player's position is again updated.
* The game is played until one player's postion becomes equal to 100, thereby declaring him/her the winner.

## Bibliography
The following sources were found to be of help :
> tutorialspoint.com  
> w3schools.com  
> Head First Python by Paul Barry  
