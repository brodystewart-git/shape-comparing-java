# shape-comparing-java
COP2805 Assignment 6 | Fall Semester, 2025 | Brody Stewart
This assignment was for my Advanced Java Programming Course at Valencia College in the Fall 2025 semester. It was for assignemtn 6, which was an assignment with a very clear outline on what it should do. Its ultimate learning goal was to explore the idea of classes, objects, comparables and inheritance. 

This program takes no inputs, but it does output some information to the user. If the user would like to edit the variables of the shape sizes, they must do so in the main function.

This is done through the Comparable abstract class Shape3d, which defines how to compare two objects by their volume, which is an undefined function. 
Two shape clases extend Shape3d, defining how volume is calculated for each through their own Volume functions. These all contain their own variables for their size data requirements (width, height, depth, etc.)
They each have a constructor which takes the variables needed to define the size when instantiating the object. 
Finally, the main function tests these classes through creating a cube and cylinder object, the two classes that are extending Shape3d. 
It then constructs them with hard-coded size variables, printing this information out for the user to see. 
Then, it compares the two objects to see which object's volume is larger, printing the result out to the user.
