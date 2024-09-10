# Snake Game Logistics

## How To Play
Use the WASD keys to move UP(W), DOWN(S), RIGHT(D), or LEFT(A). If your snake is moving UP or DOWN, your next vaild key can only be LEFT or RIGHT. If your snake is moving LEFT or RIGHT, then your next vaild key can only be UP or DOWN. There is a menu of diffeerent foods that your snake can eat that affects the snake and game points accordingly. If your snake runs into itself, you lose the game, and your score will be reported to you. 

## Menu
 - 'O' is a classic bagel --> +1 score; +1 body
 - '+' is a spicy nacho --> +5 score
 - '$' is an energy drink --> +10 score; +2 body


## Remarks
This game is currently configured for Windows. Make the files and run the Project.exe to play. If you want to run it on Mac or Linux:
 - Uncomment line 5 in makefile, and line 5 in MacUILib.h
 - Comment out line 4 in MacUILib.h

NOTE: Do not copy this code. This game is a project for a course at McMaster University, thus the Mcmaster Academic Integrity Policy must be followed. 