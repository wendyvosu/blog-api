# blog-api

Link to Hosted Site
-
https://wendyvosu.github.io/number-guessing-game/

Installation Instructions
-
-There is no installation necessary to play the game. The game can be accessed through the "Link to Hosted Site".

**How to Play**
-
### Objective
The player wins if they are able to guess the number correctly.

1. The player will choose between difficulty modes: easy, medium, and impossible. The ranges of the difficulty modes are as follows:
  - Easy: 0 - 100
  - Medium: 0 - 200
  - Impossible: 0 - 300
2. The player will input an integer guess. The input number will be compared to the randomly chosen number and return whether the number is higher, lower, or the correct number. 
3. If the player guesses incorrectly, the player loses a turn. Each time the player loses a turn, genie will take a turn guessing a number. Both the player and genie is allowed 10 turns each. Once the player is out of turns and is unable to guess the correct number, they lose to genie.

# Creation of the Game

## Wireframe

[Number Guessing Game Wireframe](https://docs.google.com/document/d/1z4IqVI4qehhktmOvKG7ohO-AGEqrgCP64zk2fTraamY/edit?usp=sharing)

Explanations of Specific Technologies
-
Built with HTML, CSS, JavaScript, and the DOM on VS Code.

Approach Taken
-
- First, I wrote out the game in pseudocode to detail how I wanted the game to function. 
- Then, I decided to build the scripts necessary for the game to function. I built the scripts into each HTML page that required it. 
- Finally, I added styles to the index and other HTML files. 

Technical Details
-
The script of the game uses four separate functions: checking the user's guess, checking the computer's guess, ending the game, and resetting the game. 

Technical Challenges
-
Preventing page refreshing once the functions have passed. 

Unsolved Problems
-
Minor styling issues.

Future Improvements
-
- Modify the script so that the user is restricted from guessing numbers which fall out of the possible range of the number. 
- Modify the script so that the computer is unable to make the same guess multiple times by using an array. 
- Additional styling adjustments. 
