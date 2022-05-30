- Open Inspect Element in Google Chrome `Ctrl + Shift + I`.
- Find Console.
- Paste this in your console:
 ```js
Runner.instance_.playingIntro = true;

 ```
#### Now trying to play the game, you will notice that the dino does not move but the score increases...

- To disable this:
```js
Runner.instance_.playingIntro = false;
```
