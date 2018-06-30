# GD50_Assignment_0

PONG Video Game.
Modified the code for assignment_0. This now makes the player2
paddle become an AI to play against. The logic for the piece
of code that was modified is as follows:

If the corner of ball is below the corner of paddle, and the paddle position isn't
overlapping/lined-up with the position of the ball:
move the paddle downwards towards the position of the ball

If the corner of ball is above the corner of paddle, and the paddle position isn't
overlapping/lined-up with the position of the ball
move the paddle upwards towards the position of the ball

else stop the movement of the paddle and wait for the ball to hit it

If the gameState is in the serve state then stope the movement of the paddle as well. 
