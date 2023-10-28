# cdio2_solo usecases

## Use Case: USC1
### Use Case Name
Play Board game

### Scope
Board game

### Level
User goal

### Primary actor
User/Player

### Stakeholder & interests
User: Wants Intuitive UI and gameplay, clear instructions and responsive gameplay.

Company/client: Wants to satisfy customer interests/needs.  

### Preconditions
None

### Success Guarantee (Postconditions)
A player has reached 3000$, and a winner has been declared.

### Main success Scenario (Basic flow)
1. Player presses button to start game
2. Player1 takes turn
3. Effects are applied to Players account
4. Game displays information about result of Player 1's turn
5. Player2 takes turn
6. Game displays information about result of Player 2's turn
7. System checks if any Player above 3000$
    7a. System finds a Player above 3000$
        1. System awards win to Player with highest $$
    7b. System does not find Player above 3000$
        1. steps 2-7 are repeated

### Extensions (Alternative flows)
*a At any time Player exits game (One way or another)
    1. Game shuts down

### special requirements
input - output response time of less than 333ms. 