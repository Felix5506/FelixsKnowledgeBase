In a currently unnamed game I am currently developing, there is a bug where one of the AI's pathfinding is not working as intended. Currently it is stuck on low friction, meaning the model will slide on the ground.


# How to Recreate the Bug
* Go to roblox studio and run the place
* Find the character with the bugged AI in the map
* Observe as it attempts to follow the player but slowly drifts off course

## Severity
This bug is medium priority for me because I think it may be possible to just integrate it as part of the character. I am not sure where to fix it in my code, but I do know that it must be part of the friction variables.

### How to Resolve
I intend to resolve this bug by either setting a static friction value everywhere, or by changing the character's animation to match a more slippery movement style. Currently, I am more likely to just leave it and animate the characters movement to match this movement pattern.

![Pathfinding script](assets/PathFindingScript.png)
Above is what my current script looks like for the AI


#### See Also
[[Audio Bug]]
