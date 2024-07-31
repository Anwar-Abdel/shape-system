# Challenge Exercise: Simple Shape System

### Objective:
Create a simple shape system using classes and methods in Python. This exercise involves creating a base class for Shape and a subclass for Rectangle.

### Requirements:
1. Shape Class:
- Attributes:
 - color (string)
- Methods:
 - __init__(self, color): Initialize the color attribute.
 - area(self): Returns 0 (to be overridden in subclasses).
 - perimeter(self): Returns 0 (to be overridden in subclasses).
- __str__(self): Returns a string representation of the shape’s color.

### Rectangle Subclass:
- Inherits from Shape
- Additional Attributes:
- width (float)
- height (float)
- Methods:
- __init__(self, color, width, height): Initialize the attributes, including those in the base class.
area(self): Returns the area of the rectangle.
- perimeter(self): Returns the perimeter of the rectangle.
- __str__(self): Override to include width and height.
