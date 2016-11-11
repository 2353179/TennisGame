# TennisGame
Unit testing exercise

Write a simplified version of a Tennis Game (think of the Wii Tennis minigame)

- A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
- The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "love", "fiteen", "thirty", and "forty" respecAvely.
- If at least three points have been scored by each player, and the scores are equal, the score is "deuce".
- If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "advantage" for the player in the lead.

*Examples:*

Initial love - love  
player1 scores > Score: 15 - love  
player2 scores > Score: 15 - 15  
player1 scores > Score: 30 - 15  
player1 scores > Score: 40 - 15  
player1 scores > Score: player 1 wins  
 
player1 scores > Score: 15 - love  
player2 scores > Score: 15 - 15  
player1 scores > Score: 30 - 15  
player1 scores > Score: 40 - 15  
player2 scores > Score: 40 - 30  
player2 scores > Score: deuce  
player1 scores > Score: advantage - 40  
player1 scores > Score: player1 wins  

player1 scores > Score: 15 - love  
player2 scores > Score: 15 - 15  
player1 scores > Score: 30 - 15  
player1 scores > Score: 40 - 15  
player2 scores > Score: 40 - 30  
player2 scores > Score: deuce  
player1 scores > Score: advantage - 40  
player2 scores > Score: deuce  
player2 scores > Score: 40 - advantage  
player2 scores > Score: player 2 wins  
