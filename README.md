# MegaRogue65
An isometric Rougelike game (and the required basic tools to make the game) for the Mega65 computer. Using FCM (Full Colour Mode) character mode and RRB (Raster-rewrite Buffer) techniques in BASIC65.

Under construction. The current status is the following: A random map creation has been implemented but the rooms still have all possible doors so it could be enhanced with randomly taking away doors (and adding a flood-fill check to verify that the rooms are still accessible). The rooms at this stage have only one type of tiles and the doors are displayed.

Update 22026.01.01.: The soon arriving Mega65 version of the original Roguecraft game has been announced, so it makes no sense to develop this Rougecraft-inspired game forward in the same direction.
I will keep this project alive but might change the game concept. The basics of the isometric layout could be useful in developing different isometric games.

## Tools:

### Ifftotiles.bas
This program loads a 32 colour IFF image (can be modified to 256 colours if needed) and creates custom FCM characters from it (places them to the $40000- area).
It saves this character data and the palette data into separate files.
RUN 9000 is an example how to load the palette data back.
The saved character data can be loaded back to the $40000- area with BLOAD command.
