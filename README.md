# Breeze Nord cursors

[Nord theme](https://www.nordtheme.com/) version of the KDE [Breeze cursors](https://github.com/KDE/breeze/tree/master/cursors/Breeze).

To install, copy the `Breeze Nord` directory to `/usr/share/icons`.


## Building the Bridge Icon set from the Inkscape SVG:

1. Ensure you have inkscape and xcursorgen installed.
2. Run build.sh in a terminal. The script may take several minutes.
3. Copy the folder created by the script (should match the name of the theme)
   to your cursors folder.

No trimming will have been done to the cursors, and X11 *may* give you
split-second glitches when switching cursors making them appear to 'jump'
for an instant. To remedy this, you will need to open any auto-generated in
gimp and re-export when with the “trim whitespace” option checked. I do not
beleive it impacts all versions of X, or Wayland.

You will need the “X11 Mouse Cursor (XMC)” plugin for GIMP installed to trim
the cursors if you choose to do so.
