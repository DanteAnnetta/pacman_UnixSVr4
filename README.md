Pacman
======

This is the original UNIX version of the Pac-Man game.  Posted to the
net.sources newsgroup as public domain in 1982 by Mark Horton.

The games was originally written by Dave Nixon while at AGS Computers
Inc., in July 1981.  It was converted to curses in Feb 1982 by Mark
Horton.

Screenshots
-----------

```
#######################################      SCORE:      0       GAME: EASY
# . . . . . . . . ### . . . . . . . . #
# O ### . ##### . ### . ##### . ### O #
# . . . . . . . . . . . . . . . . . . #
# . ### . # . ########### . # . ### . #
# . . . . # . . . ### . . . # . . . . #
####### . ##### . ### . ##### . #######
      # . # . . . . . . . . # . #
      # . # . ### - - ### . # . #
####### . # . #         # . # . #######
        . . . # B I P C # . . .
####### . # . #         # . # . #######
      # . # . ########### . # . #
      # . # . . . . . . . . # . #
####### . # . ########### . # . #######
# . . . . . . . . ### . . . . . . . . #
# O ### . ##### . ### . ##### . ### O #
# . . # . . . . . @ . . . . . . # . . #
### . # . # . ########### . # . # . ###
# . . . . # . . . ### . . . # . . . . #
# . ########### . ### . ########### . #
# . . . . . . . . . . . . . . . . . . #      gold left =    185
#######################################      delay = 500, refresh =   1
@  @

```

Instructions
------------

Attention: you are in a maze, being chased by monsters!

There is food scattered uniformly in the maze, marked by ".".
One magic potion is available at each spot marked "O". Each potion will
enable you to eat monsters for a limited duration. It will also
scare them away. When you eat a monster it is regenerated, but this takes
time. You can also regenerate yourself 3 times. Eating all the monsters
results in further treasure appearing magically somewhere in the dungeon,
marked by "$". There is a magic tunnel connecting the center left and
center right parts of the dungeon. The monsters know about it!

    Type:       a or j  to move left
                d or l  to move right
                w or i  to move up
                s or k  to move down
                q       to quit

    Type:       1       easy game
                2       intelligent monsters
                3       very intelligent monsters

Credits and recognitions
------------------------

Mainly grateful to troglobit for adapting the original code of the game so that it could be compiled without problems on more modern systems than the original.

[https://github.com/troglobit]()
