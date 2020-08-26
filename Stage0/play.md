# Play Game

## Feature

Begin Game

## Acceptance Criteria

Player able to play the game

### Scenario: Players enters in single-mode

  Given - Player starts the game

  When - Single-mode is selected as the game mode

  Then - A bot is assigned to play the game as Player 2

### Scenario: Players enters in player mode

  Given - Player starts the game

  When - Player mode is selected as the game mode

  Then - A player first logs in is assigned to be player 1 and second as player 2.

### Scenario: Players start the game

  Given - Player starts the game

  When - Player hit the ball to the wall of the opposite player

  Then - A goal is added to the scorecard of the player.

### Scenario: Players scores 10

  Given - Player starts the game

  When - Scorecard reaches 10 of any of  the player

  Then - The player whose score is 10 is declared as the winner and level is incremented.
  AND Player 2 level is decremented.

### Scenario: Players exits the game in middle of the game

  Given - Players are playing the game

  When - A player exits the game

  Then - The second player is declared as winner and level is incremented.
  AND Player 2 level is decremented.
