# MegaRogue65
An isometric Rougelike game (and the required basic tools to make the game) for the Mega65 computer. Using FCM (Full Colour Mode) character mode and RRB (Raster-rewrite Buffer) techniques in BASIC65.

Under construction.

Tools:

Ifftotiles.bas
This program loads a 32 colour IFF image and creates custom FCM characters from it (places them to the $40000- area).
It saves this character data and the palette data into a aseparate files.
RUN 9000 is an example how to load the palette data back.
The saves character data can be loaded back to the $40000- area with BLOAD command.
