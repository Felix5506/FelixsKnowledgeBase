There is a known bug where audio will become muted from various sources on a phone when a game of connections is launched.

![User bug report describing audio muting on game launch](AudioBugReport.png)
Above is a users description of the bug

# How to Recreate the Bug
* The user must be on either Apple or Android mobile devices
* Open the Spotify app and start playing any song
* Open discord and launch the connections game
* Complete authentication and all sound will be muted

## Apps Affected
I have tested the bug on both apple and android devices, and the bug only seems to occur exclusively when Spotify is also open on the device. I assume that there is a correlation between Spotify audio and opening applications on discord.

### How to Resolve
Unfortunately I have found no way to resolve the issue from within my code, the best route to take on the client side is to close Spotify while in the application and you will continue to get sound from the other applications.


#### See Also
[[Authentication Bug]]
