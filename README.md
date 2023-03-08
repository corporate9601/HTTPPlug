# HTTPPlug
create a localhost http server for old school runescape which saves data to a http server port 8080.

credits to @SlyAutomation 

New:
- handlePlayers (localhost:8080/players)
- handleTiles (localhost:8080/tiles)


what is handeTiles?

I use it for my walker, so you can run 1-5 tiles in any of the allowed directions in runescape (up, down, left right, and the 4 diagonals)

You should calculate the gradient between your player X Y and the X Y coords of the next point in the path. Then 'snap' this gradient (not sure a better word lol) to either a vertical, horizontal, or diagonal pos/negative value and then workout the direction you need to run

You can make a great walker this way! the screen and camera can be at any angle 

I only do max 5 tiles because there should always be 5 tiles in every direction on screen no matter the zoom ( i may be wrong) plus if you update while you're running there's no need to have any more. while it's running 5 tiles it should recalculate and keep clicking new tiles to run to so it doesn't stop running.
