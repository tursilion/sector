20110414

This is a simulation of the old game "Code Name: Sector". In it,
you attempt to hunt and sink a hidden sub with 1-4 players, using
only a range finder and some deduction.

I've made it mostly play like the original, enough, I believe, that
the original documentation will suffice. There is one area that is
fairly different, and I did this because the XB display update is
a bit slow, and that is during the firing sequence.

Pressing AIM displays 'AIM'. While this is up, the normal left and
right keys to turn the compass affect your aim, not your direction.
You may exit AIM mode by pressing Recall, you are not committed yet!
This is contrary to the original game, where you would repeatedly
press AIM to change the direction.

During AIM mode, press FIRE. The game will ask you to enter depth,
which is 1-3. This is contrary to the original game, which would
sequence/flash the depths during AIM mode, and fire immediately.

If you try to move more than once in a turn, it will flash "NEXT".
If you try to fire more than once in a turn, it will ignore you.

The other differences are small. 'F' ranges (ranges that are ok
to fire) are indicated with "F OK" in the status window, rather than
an F in the range display. A collision automatically displays your
relocated course and bearing rather than relying on you to press
Recall (SOS does require RECALL however!). You can only set the 
Evasive Sub option at the beginning of the game, and if you want to
reveal the sub's location, Give up, but that ends the game.

Finally, I don't have graph paper that is 50x50, so I made it configurable.
You need at least 30x30 cells to play, up to 74x74. Remember, North
Latitude counts UP from 25 at the bottom, and East longitude counts
RIGHT from 25. (Although you can flip it any way you like, the charting
is for your reference.)

I didn't put computer charting in for two reasons. First, time. ;)
But secondly, the charting is the whole art of the puzzle. If the
computer draws the charts, it might as well be playing by itself, as
it will give away the answer.

In case you don't have the docs, the basic game play, per ship, is:

1) Press range - this is the distance to the sub. Range is measured
as a square around the ship - so mark off only 90 degree and 45 degree
lines, and draw the box. Further, the sub will not venture within
5 units of the edge of the map.
2) Set course and speed, and Move ship. Do not collide with other ships,
if you do, you will be knocked to a random location and course.
3) Press range again. The sub has not moved, so use the new range to
update your chart and eliminate impossible positions.
4) If you are within 2 units, and the sub is in a 45 degree or 90
degree line to you, the system will display "F OK" when you press
range. If this is set, you may safely fire. If you fire when "F OK"
if not valid, you will ALWAYS miss!
5) To fire, first press AIM (if you forget, AIM mode enters for you
automatically). Select the direction with left and right, then press
FIRE. The system will ask you for the depth. The sub resides at a
depth of 1, 2 or 3, so press that value.
6) A hit displays as SUB! and ends the game. If you fire in the correct
direction and have a direct shot (F OK), but get the incorrect depth,
the system will display "OFF" and a number indicating how far off (1
level or 2 levels).
7) If you fire the wrong direction, out of range, or without a
clear shot (F OK), "SOS!" lights up and the system will relocate you
to a random position and course. (The sub 'retaliates'). Press RECALL
to see your new position.
8) When done, press NEXT SHIP. The sub will move one unit but will
stay at the same depth. The sub will not change course unless it
reaches 5 units of the border, then it will turn to a new course.
9) EVASIVE SUB makes the game more difficult by allowing the sub
to turn 45 degrees every time a shot is missed (OFF or SOS).
