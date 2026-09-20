There is a known bug in the connections game where users can relaunch the game multiple times and reset their game state

![User bug report describing audio muting on game launch](../assets/SaveStateBugReport.png)
Above is a users description of the bug

# How to Recreate the Bug
* The bug can occur on any device, mobile or pc
* Open the discord app using any account and run /connections
* Launch the game
* Start playing the game and make a guess
* Leave the game
* Start the game again and your progress will be reset to a new board state

## Exploitability
Users can exploit this bug to get more guesses on a tough puzzle, significantly reducing the difficulty of it. This bug is of low importance overall because most users would just look up the answers anyways if they wanted to exploit the bug.

### How to Resolve
Users can simply finish the puzzle to the end, although if I were to fix it on the server side, I would likely add a save state for each guess, rather than the complete/incomplete system I have implemented currently.

#### See Also
[[End Game Bug]]