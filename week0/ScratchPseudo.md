# Scratch Project

## Fish
1. When green flag is clicked
  * Show
  * Switch backdrop to Underwater1
  * Go to specified location
  * Broadcast "Avoid The Shark!"
2. When I receive "Game Over"
  * Hide
  * Switch backdrop to Water and Rocks
3. When I receive "You Win"
  * Hide
  * Switch backdrop to Boardwalk
4. When up arrow pressed
  * Change y by 20
5. When down arrow pressed
  * Change y by -20
6. When right arrow pressed
  * Change x by 20
7. When left arrow pressed
  * Change x by -20
### Shark2
1. When green flag  is clicked
 * Set glideSpeed to 5
 * Hide
 * Always be aware that game is over if the shark is touching the fish
2. When I receive "Game Over"
 * Hide
 * Stop all
4. When I receive "Avoid the Shark!"
 * Switch costume
 * Point towards fish and set roatation style from left to right
 * Repeat sharkGlider and decreaseGlideSpeed sequence 5 times
 * Set glideSpeed to 5
 * Broadcast "SecondShark"
 * Repeat sharkGlider and decreaseGlideSpeed sequence 20 times
 * Broadcast "You Win!"
 * Hide
 * Stop all
