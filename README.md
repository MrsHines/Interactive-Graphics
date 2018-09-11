# Interactive-Graphics
Set this program up like the ones we have done so far.  Each function should be called from the main function. The Input specifications for each program indicate the information that comes from the user with either Entry objects or getMouse().  All output should happen in the window as Text objects.  

Make sure you have comments at the top with the file name, your name, and a short description of the file.
Make sure you have a comment before each function with a description of the function.
Logically divide your programs with whitespace and provide comments to make your code easy to follow.  

Function #1:  Trig
Write a program that computes the intersection of a circle with a horizontal line and displays the information textually and graphically.
Input: radius of circle and y-intercept of line
Output: 
Draw a circle centered at (0,0) with the given radius in a window with coordinates running from -10, -10 to 10, 10.  
Draw a horizontal line across the window with the given y-intercept
Draw the two points of intersection in red
Print out the x-values of the points of intersection
x = sqrt(r^2 - y^2)

Function #2: LineSegment
Write a program that allows the user to draw a line segment and then displays some graphical and textual information about the line segment.
Input: two mouse clicks for the end points of the line segment
Output: 
Draw the line segment
Draw the midpoint in cyan
Print the length and slope of the line.

Function #3: Rectangle
Write a program that displays information about a rectangle drawn by the user.
Input: 2 mouse clicks for opposite corners of the rectangle.
Output:
Draw the rectangle.
Print the perimeter and the area of the rectangle.

Function #4:  House
Write a program that allows the user to draw a simple house using 5 mouse-clicks.  The first two clicks should be the opposite corners of the rectangular frame of the house.  The third click will indicate the center of the top edge of a rectangular door.  The door should have a width that is 1/5 the width of the house.  The fourth click will indicate the center of a square window.  The window is half as wide as the door.  The last click will indicate the peak of the roof.  The edges of the roof will extend from the point at the peak to the corners of the top edge of the house frame.
