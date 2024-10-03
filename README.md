Animated Bouncing Balls Project
Overview
This project demonstrates a simple web page featuring two bouncing blue balls using HTML, CSS, and JavaScript. The balls move diagonally within the window, alternating directions once they reach the edges of the screen.

Files
index.html: The main HTML file containing the structure, style, and JavaScript logic.
Structure
The project consists of two div elements (ball1 and ball2) styled to appear as blue circles (using border-radius: 50%).
These circles are positioned absolutely on the page and move diagonally using JavaScript.
Code Breakdown
HTML
Defines the structure with two div elements representing the balls (ball1 and ball2).
The balls are given inline styles for size, color, and absolute positioning.
CSS (Inline Styling)
The div elements are styled as circles with:
background-color: blue;
border-radius: 50%;
height: 100px; and width: 100px; (making them 100x100px circles)
Positioned absolutely with position: absolute; and z-index: 5; to ensure they are on top of other elements.
JavaScript
Variables:

velocity: Speed of the ball's movement (set to 2).
position: Current position of the balls (initially 0).
moveleft and moveright: Used to track and reverse the ball's direction.
move1 Function (for ball1):

Moves the ball diagonally within the window, alternating its direction when it reaches the edges (defined as position >= 95 or position <= 0).
Updates the left and top positions of ball1.
move2 Function (for ball2):

Similar to move1, but works for ball2. Moves diagonally and reverses direction when reaching the edges.
setInterval:

Calls move1 and move2 functions every 100ms to animate the motion of the two balls.
How to Run
Download or copy the code into an index.html file.
Open the file in any modern web browser.
You should see two blue balls moving diagonally on the page.
Possible Improvements
Add smoother animations using requestAnimationFrame instead of setInterval.
Make the animation more responsive or allow the balls to move at different speeds or trajectories.

