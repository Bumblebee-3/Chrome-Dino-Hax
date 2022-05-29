# CHrome-Dino-Hax
## A simple method to Skam your friends (and astound them too) by "hecking" Chrome's Dino Game.

#### Hello, I am going to show you how to "hack" google dino game in few easy steps.

### Removing Obstacles.
- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
var originalGameOver = Runner.prototype.gameOver // backing this up, Will be needed to stop the game...
Runner.prototype.gameOver = function(){} // changing it to an empty finction XD
 ```
#### Now trying to play the game, you will notice that the dino does not detect the obstacles...
### Increasing Speed.
- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
Runner.instance_.setSpeed(5000)//sets the dino's speed to 5000 points per second
 ```
#### Now trying to play the game, you will notice that the dino's speed Increases...
### Stopping The Game
#### After some time, you may want to stop the game, to save the score. Because we have removed obstacles, the game will keep on going on forever. So, now we are going to use the variable defined earlier as `originalGameOver` to edit the GameOver function.
- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
Runner.prototype.GameOver = originalGameOver //resetting the gameOver function.
```
#### Now play, and the obstacles will be back. Then collide with the obstacle...

## THE END - Hope you liked this simple tutorial. If you did, please star this repo and share it with friends :)
