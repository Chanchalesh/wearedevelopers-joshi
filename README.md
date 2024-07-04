# wearedevelopers-joshi

To determine which points from the provided JSON dataset fall within the "100" logo, we need to define the areas representing each part of the logo and then check which points lie within these areas. The "100" logo consists of a rectangular "1" and two circular "0"s.

The coordinates of the logo and its parts are:

The "1" is a vertical rectangle:

Bottom-left corner at (145, 75)
Width: 20
Height: 150
The first "0" is a circle:

Center at (250, 150)
Radius: 75
The second "0" is a circle:

Center at (410, 150)
Radius: 75
We will check each point in the provided dataset to see if it lies within any of these three parts of the logo.

Let's write a script to process this data and count the points that lie within the "100" logo. We'll start by loading the JSON data and then define functions to check if a point lies within the rectangle or within either of the circles.

Here is the plan:

Load the JSON data.
Define the function to check if a point is inside the rectangle (representing the "1").
Define the function to check if a point is inside a circle (representing the "0"s).
Count the points that satisfy any of the above conditions.
Let's proceed with the implementation.

There are 36 points from the given dataset that lie within the "100" logo.
