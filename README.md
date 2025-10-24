# Number Guessing Game

# Initial Branch Structure
The main branch contains the initial implementation for the game.
From there we have multiple branches:
1- main -> The starting point with basic game functionality
2- feature1 -> First feature branch adding quit and replay capabilities
3- dev -> Development branch for player encouragement features
4- feature2 -> Second feature branch implementing attempt limitations
5- feature3 -> Third feature branch adding a hint system
6- hotfix -> Bug fix branch correcting the random number generator

# Changes in each Branch
main:
-Initial implementation of the Number Guessing Game
-Players guess a number between 1 and 100
-Provides "Too high" or "Too low" feedback
-Tracks number of attempts

feature1:
-Added quit functionality
-Implemented play-again loop 
-Improved user feedback messages

dev:
-Added encouraging messages for players
-Enhanced user experience with positive feedback

feature2:
-Introduced maximum attempt limit (10)
-Implemented game over condition when all attempts are exhausted

feature3:
-Implemented hint system to assist players
-Provides clues during gameplay
-Has a bug in Utils.randomInt() method

hotfix:
-Fixed critical bug in Utils.randomInt() method
-Changed formula from (max - min) to (max - min + 1)
-Now the maximum value (100) can be selected as the target number
