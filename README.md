# comp115_project1
Basketball Court Drawing with Turtle
This Python script utilizes the Turtle module to draw a basketball court with various elements such as players and random symbols on a black background. The script creates a graphical representation of a basketball court with the following components:

Court Boundary: A white rectangle outlines the boundaries of the basketball court.
Basketball Hoop and Backboard: Two basketball hoops with backboards are drawn on opposite ends of the court.
Center Circle: A large orange circle represents the center circle of the court.
Court Dividers: White lines are drawn vertically and horizontally to divide the court into sections.
Players: Blue and green plus signs represent players on the court. These are drawn at specific coordinates to simulate player positions.
Random Symbols: Random symbols (e.g., !, @, #) in various colors are scattered across the outer black background to add visual interest.
How It Works
The script consists of several functions:

draw_rectangle(x, y, width, height, color): Draws a rectangle at the specified coordinates (x, y) with the given width, height, and color.
draw_circle(x, y, radius, color): Draws a circle at the specified coordinates (x, y) with the given radius and color.
draw_player(x, y, symbol, color): Draws a player symbol at the specified coordinates (x, y) with the given symbol and color.
draw_random_symbols(num_symbols): Draws random symbols with random colors across the outer black background.
The main code section calls these functions to draw the basketball court elements.
