# Project:Polygon Area
## Poject 1: simple polygon area and perimeter calculater
![Pentagonn](https://user-images.githubusercontent.com/99794453/182675547-2198e4d6-9cdb-429b-b75d-c39671f67166.jpg)
In convex polygon All interior angles are  less than 180 degress. 
In this project our main aim is to find the area and perimeter of polygon. first we declare the vertices 
and second we declare each side of two points. we can find the distnace between every points automatically and we can get the length of each side.
By adding all sides lengths we get the perimeter of the polygon 
To find the area first we can divide the polygon into trinagle shapes after that we can find the area of every triangle by adding all these areas to get the Area of each polygon.
## Project 2: convex and concave polygon area and perimeter calculator
![images](https://user-images.githubusercontent.com/99794453/182679801-c11e434d-f2cf-4bd9-bc12-d29a4d4ac927.png)
convex:All interior angles are less than 180 degrees
concave: All interior angles are more than 180 degrees
complex: set of line segments (sides) connected such that any two segments crossed each other. except edges intersect.
In this project our main aim is to find the area and the perimeter of polygon we declare the vertices 
and seconds we can find each side of the two points, After declaring the points we can check the shape of the polygon 
first check that if any line segment intersect each other or not, if they intersect each other it is called complex
All are equal to 0 or all are less than 0 then such type of polygon called convex otherwise it is called concave.
we can find the perimeter by adding all segments lengths
we can find the area of polygon by using shoelace algorithm
## shoelace algorithm
![Screenshot 1](https://user-images.githubusercontent.com/99794453/182764243-f46cdb10-053a-459e-aef1-9381189cdded.png)

The shoelace formula or shoelace algorithm is a mathematical algorithm to determine the area of the simple polygon whose vertices are described by their Cartesian coordinates in the plane.
This method consists of cross-multiply corresponding coordinates of the different vertices of a polygon to find its area. It is called the shoelace formula because of the constant cross-multiplying of the coordinates making up the polygon, like tying shoelaces. (See table below). This algorithm has applications in 2D and 3D computer graphics, in surveying or in forestry, among other areas.
![Screenshot (69)](https://user-images.githubusercontent.com/99794453/182764281-2b2456b5-e5b2-4091-9a62-3b4faa89214a.png)

To apply the shoelace algorithm you will need to:
List all the vertices in anticlockwise order. (e.g. A,B,C,D,E) in a table, and note the x and y coordinates in two separate columns of the table,
Calculate the sum of multiplying each x coordinate with the y coordinate in the row below (wrapping around back to the first line when you reach the bottom of the table),
Calculate the sum of multiplying each y coordinate with the x coordinate in the row below (wrapping around back to the first line when you reach the bottom of the table),
Subtract the second sum from the first, get the absolute value (Absolute dfference |sum1-sum2|,
Divide the resulting value by 2 to get the actual area of the polygon
![screen](https://user-images.githubusercontent.com/99794453/182765098-1976d57c-e015-4d5b-8932-14f090433d63.png)
