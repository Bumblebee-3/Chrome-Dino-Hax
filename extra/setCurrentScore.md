### To set the current game score:
- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
Runner.instance_.distanceRan = 98765 / Runner.instance_.distanceMeter.config.COEFFICIENT//replace 98765 with whatever you want (must be less than 99999)...

 ```
#### Now trying to play the game, you will notice that the score goes to the inputted integer...
