# Blook Script

### What is this?
This is an experimental branch of Blooket Cheats that use a custom compiler and runtime to get around Blooket's CSP eval block

### What's the benefits?
* No more manually updating cheats!
* Firefox users no longer have to worry about the max bookmark limit
* All cheats can now be ran by the same script, just by changing one value
* Anti-Suspend by [CryptoDude3](https://github.com/CryptoDude3/)

### How do I get started?
If you like to use the Devtools console, copy the script found in [run.js](/run.js), or if you like or can only use bookmarks, copy [run.min.js](/run.min.js) and replace
```
const toRun = "gold/setGold";
```
with
```
const toRun = "pathTo/anyCheat";
```
To get the path to your selected cheat, first navigate to the cheat's .png file in the [out/](out/) directory. You should be at a URL similar to: https://github.com/005Konz/blook-script/blob/main/out/gold/setGold.png
The path is the part of the URL after `out/` and before `.png`

### How do I make a javascript bookmarklet?
Make a new bookmark, type `javascript:`, then paste the script to run.
Some browsers remove the `javascript:` after pasting, so you can also paste, then do `Ctrl + A`, press the left arrow, and type it at the beggining.

### This is cool. Discord?
https://discord.gg/jHjGrrdXP6