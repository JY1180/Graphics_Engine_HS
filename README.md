From my computer graphics class (has not ended as of 1/7/2024)

commands are carried out like this:
command
values
(ex.)
sphere
250 250 0 150

list of commands:
push: Takes no additional values. It saves all the transformations applied.

pop: Takes no additional values. It removes the recent transformation applied.

line: Requires six doubles (x0, y0, z0, x1, y1, z1). It draws a line between these points

box: Requires six doubles (x0, y0, z0, x1, y1, z1). They represent the coordinates of two opposite corners of the box.

sphere: Requires four doubles (x0, y0, z0, r0). They represent the center and the radius of the sphere.

torus: Requires five doubles (x0, y0, z0, r0, r1). They represent the center, the major radius (r0), and the minor radius (r1) of the torus. If you think of it like a donut, the major radius is the distance from the center to the edge, while the minor radius is the thickness of the edable donut part.

circle: Requires four doubles (x0, y0, z0, r0). They represent the center and the radius of the circle. (Note: this is 2d while sphere is 3d)

bezier/hermite: Requires eight doubles (x0, y0, x1, y1, x2, y2, x3, y3,). They represent the control points for the curve type chosen. 

scale: Requires three doubles (x0, y0, z0). They scale all the shapes you make after the command in those directions.

move: Requires three doubles (x0, y0, z0). They move all the shapes you make after the command in those directions.

rotate: Requires two values: ether (x0, y0, or z0) and an angle in degrees (theta). (x0, y0, or z0) represent the axis of rotation and (theta) represents the angle moved (can be negitive)

clear: Takes no additional values. It clears the screen.

display: Takes no additional values. It displays the screen.

save: Requires a string (ex. pic.jpg). It saves the current screen with the file name

comment: starts with '#'. Everything after that is ignored that is on the same line as the '#'