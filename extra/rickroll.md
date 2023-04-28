### To Rickroll people if they loose:
- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
var id="zL19uMsnpSU";
Runner.prototype.gameOver = function(){window.location.href="https://www.youtube.com/watch?v=" +id;}
 ```
#### Now trying to play the game, if someone looses, they get rickrolled...
