# Worderly

## Introduction
(TODO : write some intro, your favorite food etc.)  

## User Manual

### Running The Program

#### Command
Run the program using the command:
Example  :
> python3 worderly.py

#### Options

(TODO : list each option and explain. or copy paste the result of -h)  
Example  :
> -h, --help  blah blah  
> -d, --debug blah blah  

### User Interface

#### Main Menu
(TODO :  maybe add screen shot here ?)  
(TODO : explain what this interface is for)  

##### Options

###### [P] Play Game
Loads the puzzle and starts the game.

###### Options2
(TODO : explain option2)  

###### Options3
(TODO : explain option3)  

##### How To Exit
Enter [Q], or press [ctrl + c] to close program.

#### Puzzle Game
(TODO :  maybe add screen shot here ?)  
Selecting [P] from the main menu starts the game.  
A puzzle with specified size and word count is shown. 

##### Game Mechanics
(TODO : briefly explain game mechanics)  

##### Puzzle Solved
(TODO : explain what happens when puzzle is solved. option to restart game)  

##### Game Over
(TODO : explain what happens when no more lives. option to restart game)  

##### High Score
(TODO : briefly explain what happens when high score is achieved)  

##### How To Exit
Press [ctrl + c] for prompt to return to main menu or exit program.  
Press [ctrl + c] twice to exit program.  

#### Leader Board
Selecting [L] from the main menu displays the leader board. 
The leader board shows top 20 players and their high scores. 

##### How To Exit
Press [ctrl + c] for prompt to return to main menu or exit program
Press [ctrl + c] twice to exit program

## About The Code

### Program Files

The program is made up of the following files :

- worderly.py  
(TODO : briefly explain what this file is for)  
- file2.py  
(TODO : briefly explain what this file is for)  
- file3.py  
(TODO : briefly explain what this file is for)  

### Classes

The program uses the following classes 

- Puzzle  
(TODO : briefly explain what this class is for)  
- class2  
(TODO : briefly explain what this file is for)  
- class3  
(TODO : briefly explain what this file is for)  

### Dictionary Management

(TODO : briefly explain how you manage dictionary. key:word length, value:list of words)  

### Word Generation

(TODO : briefly explain how you generate words.)  

- Initial Word  
(TODO : briefly explain how you generate initial word, randomnness)  
- Additional Puzzle Words  
(TODO : briefly explain how you generate additional puzzle words, randomnness, orientation)   

### Word Placement

(TODO : briefly explain how you insert words on puzzle)  

- Initial Word  
(TODO : briefly explain how you insert initial word. centering)  
- Additional Puzzle Words  
(TODO : briefly explain how you insert additional puzzle words. algorithm for placement check)   

# Unit Tests

Run the unit tests using the command:
Example  :
> pytest

Unit tests are created for the following entities :  

## Puzzle

### Unit Test File
Unit tests for the puzzle are written in file [lib_puzzle_test.py].  
There are xxx unit tests for this entity.

### Unit Test Items

#### Puzzle Validity
(TODO : list all items that test for puzzle creation/validity, limits)  

#### Game Play/State Management
(TODO : list all items that test for game play/state management)  

#### Accuracy Test
(TODO : list all items that test for 100% valid puzzle generation. attempts : 100x)  

#### Others
(TODO : list all items that test for others)  

## Leader Board

### Unit Test File
Unit tests for the puzzle are written in file [lib_leaders_test.py].  
There are xxx unit tests for this entity.

### Unit Test Items

#### Leader Board Validity
(TODO : list all items that test for leader board creation/validity, limits)  

#### Leader Board Management
(TODO : list all items that test for leader board update/get etc)  

#### File I/O
(TODO : list all items that test loading and saving file)  

#### Others
(TODO : list all items that test for others)  


# Bonus Features

1. Main Menu  
(TODO : brief explanation)  

1. Leader Board  
(TODO : brief explanation)  

1. Persistent Leader Board  
(TODO : brief explanation)  

1. Game Restart  
(TODO : brief explanation. when game ends, or ctrl + c then retry from Main Menu)  

1. Game Exit  
(TODO : brief explanation. ctrl + c or from Main Menu)  

1. Colors  
(TODO : brief explanation) 

1. Omniscient Mode  
(TODO : brief explanation. -d, --debug switch) 

1. Specify Dictionary File  
(TODO : brief explanation. -f option) 

1. Specify Number of Puzzle Words  
(TODO : brief explanation. -w option) 

1. Specify Number of Puzzle Rows  
(TODO : brief explanation. -r option) 

1. Specify Number of Puzzle Columns  
(TODO : brief explanation. -c option) 

1. Show Command Help  
(TODO : brief explanation. -h option) 

# Citation

1. Whiazel Nangpi, Maia Nangpi, Mica Nangpi, Marlon Nangpi  
Helped in user testing, writing manual, feeding me.

2. Online References  
(TODO : list all references) 
Used the following pages for coding reference.  
	- www.geeksforgeeks.org
	- stack overflow
	- and a partridge in a pear tree
	- etc
