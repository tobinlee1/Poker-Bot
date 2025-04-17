# Updates
## March 21st
Agent has a higher Q value for one of three actions: CALL, RAISE, FOLD.

Durng testing agent will always pick the action of highest Q-value. 
The same action is taken during testing even with different starting states.
Current action selection is deterministics, choose highest q-value.
Very possible due to poor reward function and lack of training

## April 17th
make everythign simpler

reward function: win -> 1, lose -> -1

possible training methods:
  generate random poker hands and run out and train agent
  fix one agent when training
