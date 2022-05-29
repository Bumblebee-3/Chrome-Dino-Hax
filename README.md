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
