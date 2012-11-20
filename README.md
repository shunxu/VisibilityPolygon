%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Visibility Polygon from a Given Point -- Christine

--Implementation of the paper:
    A Linear Algorithm for Computing the Visibility Polygon from a Point
				        H. EL GINDY AND D. AVIS

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

Instructions:

1.	Fist click Draw -> Polygon, then you can enter vertices of a SIMPLE polygon in CW(clockwise) order using the GUI interface. 

2.	Second, click Draw -> Point, to specify the position of the visibility point.

3.	Third, click Option -> Visibility from a Given Point, then the visibility polygon will be shown, otherwise, error messages will be shown on the console window. The original polygon will be shown in blue, and the visibility polygon will be in red.

4.	You can repeatedly use the same polygon to view different visibility result due to different position of the point. The way to do so is after re-locate the position of the point, repeat step 3, then new result will be shown.

Options:

Open	---	Open an existed ".vp" file, whose first line is the number of points n, and whose next n lines are the x y coordinates for each point. Also, you can specify the next i+1th line to be the x y coordinate of the visibility point inside the polygon. See attached sample test files.

Save	---	Save the current polygon and the visibility point into a ".vp" file, whose format is the same as indicated above.

Exit	---	Exit the entire program.

Clear	---	Clear the current graph, including all the vertices of the polygon and the visibility point.

Select	---	Instead of inserting points into polygon or modify the position of the given point, you can do nothing when you click the canvas.

Visibility from a given point	---	Do the visibility computation based on the shape of the current polygon and position of the given point, then show the result.