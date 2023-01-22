# svg2ReGIS
Script to convert an SVG file to ReGIS graphics commands for DEC terminals

Usage:
./svg2ReGIS.py SVGFileName -s scalevalue -f -e

-x - origin point for X

-y - origin point for y

-s - sets the ammount the image should be scaled by. Provide a 0 for this argument to fit the ReGIS window (800x480)

-f - Flag. Provide it to fill in the polygons drawn

-e - Flag. Provide it to escape the ESC character. It just replaces \033 with \\033 in the output. Useful if you want to print it out with something like printf

-c - Flag. Provide to disable clearing the screen before starting to draw

