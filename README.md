Generate Gimp/Inkscape palette for Tailwind CSS
===============================================

A palette of Tailwind CSS V3 colors for Gimp and Inkscape.


Installing the palette (Inkscape)
---------------------------------

Open Inkscape, go to "Edit", "Preferences", "System" and find the path for "user palettes".

Copy `tailwindcssv3.gpl` into that directory.

Restart inkscape, you should now see the palette available when selecting the palette (hamburger menu, bottom right)


Generating the palette
----------------------

I got the tailwindColors object from https://github.com/tailwindlabs/tailwindcss/blob/master/src/public/colors.js, and tweaked it (reordered it to move grays to the bottom, removed the non-object properties).

Generated the `.gpl` file with `node palette.js > tailwindcssv3.gpl`.
