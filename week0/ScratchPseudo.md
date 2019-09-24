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
3. Define sharkGlider
 * Set yValue to random number between -180 and 180
 * Go to x = 220 and selected yValue
 * Show
 * Glide to x = 240 and selected yValue in glideSpeed seconds
 * Hide
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
#### Shark3
1. When green flag is clicked
 * Hide
2. When I receive "SecondShark"
 * Set size to 100%
 * Point towards fish and set rotation style from left to right
 * Repeat sharkGlider sequence 20 times
 * Hide
 * Stop all
3. When I receive "SecondShark"
 * Always be aware that game is over if the shark is touching the fish
4. When I receive "Game Over"
 * Hide
 * Stop all
5. When I receive "You Win!"
 * Hide
 * Stop all
