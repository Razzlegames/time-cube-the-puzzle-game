![http://i656.photobucket.com/albums/uu285/elyk1212/TimeCube/menu.png](http://i656.photobucket.com/albums/uu285/elyk1212/TimeCube/menu.png)
![http://i656.photobucket.com/albums/uu285/elyk1212/TimeCube/TimeCube_screenshot4.jpg](http://i656.photobucket.com/albums/uu285/elyk1212/TimeCube/TimeCube_screenshot4.jpg)

### Old Man Rant... ###
You are all educated stupid!  Your ignorance of 4 day TimeCube the Game is Evil!  You worship a Tetris God with shapes other than Cubes.  Man evolves from teenager, teenager evolves from child... old man blows a gasket....

**All hail TimeCube!**

<a href='http://www.youtube.com/watch?feature=player_embedded&v=PNUQ3_vNbc0' target='_blank'><img src='http://img.youtube.com/vi/PNUQ3_vNbc0/0.jpg' width='425' height=344 /></a>

## If you like this game can you please vote for it on wololo ? ##
http://wololo.net/talk/viewtopic.php...6932&start=150

### Description ###
Homebrew PSP Puzzle Game Featuring multiplayer adhoc competitive play and single player modes.

This is my first full game. I have designed all the graphics, composed all the music (LMMS), written the image parsing, etc, while using just the GU and building my own engine from the ground up. Due to this, I may not have as many crazy features as if I used a pre-built engine

I had released TimeCube just previous to learning about the competition, so I used this as an excuse to add quite a few features:

### Additions in this version ###
  * Adhoc Multi-player
  * Particle Engine (yes blocks spark and create fun effects!)
  * A new Font engine
  * Old man effects
  * Ominous Voice samples
  * New menu Graphics
  * New paused Graphics
  * New Backgrounds
  * New Goofy Gene Ray quotes

The single player is fun... but the MultiPlayer is where it's at!

The Multiplayer addition was obviously the most challenging addition... I think you will also find it is the most fun! If you like Bust-A-Move, you will love TimeCube!


### Multiplayer rules ###
Get 4 or more matches as fast as possible (with chaining falling blocks if you can)!
Get matches faster than the other player, and blocks will fly on their screen, filling it up and securing your dominance!
The last survivor is the winner!!


### Known issues ###
  * The Server will not exit to menu when you push home when connected in multiplayer mode.  Seems like the Callback won't exit and is blocked on I/O ?  Probably just need to check the exit flag from the exit callback.

  * In Server mode, it's possible to wait for a connected PSP and not be able to exit (if the other PSP's power is turned off or decides to exit).  Option to quit waiting will be added.

If you are interested in the code, please see here:
http://code.google.com/p/razzle-engine/source/browse/#svn%2FRazzlePuzzle%253Fstate%253Dclosed
