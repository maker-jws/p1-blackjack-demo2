# Your choice of game
Black Jack 

## User stories 

1. As a player, I would like to start the game when I am ready
1. As a player, I would like to review the rules of how this version of the game will play
1. As a player, when I am ready I would like to be dealt 2 cards
1. As a player, I would like to hit or stay depending on my current hand
1. As a player, after I stand, I would like to know if I won, or the house won. 
1. (ICEBOX), I would like to buy chips based on my current budget
1. (ICEBOX), ...

## A wireframe of your "main" game screen.

![](./docs/assets/Blackjack%20Score.png)

## Pseudocode for the overall game play.

1. SETUP 
    1. Notes about global variables, state, etc

1. INIT
    1. Create deck
    1. Shuffle deck
    1. Deal player and computer

1. RENDER

    1. Populate game board
    1. Display play button
    1. Display start hands (player and dealer)

1. HIT
    1. Add listener
    1. calculate current hand
    1. update total
    1. determine bust

1. CALCULATE HANDS
    1. Notes about what variables and state will be read / affected

1. STAND
    1. add listener
    2. function calls

1. DECLARE WINNER

1. PLAY AGAIN

1. ICEBOX FEATURES
    1. Display card graphics
    1. Hide cards 
    1. Betting setup and implementation
