# 0x0C. Python - Almost a circle
# Description
What you should learn from this project:

What is Unit testing and how to implement it in a large project
How to serialize and deserialize a Class
How to write and read a JSON file
What is *args and how to use it
What is **kwargs and how to use it
How to handle named arguments in a function
# 0. If it's not tested it doesn't work
All your files, classes and methods must be unit tested and be PEP 8 validated.
# 1. Base class
Write the first class Base:
# 2. First Rectangle
Write the class Rectangle that inherits from Base:
# 3. Validate attributes
Update the class Rectangle by adding validation of all setter methods and instantiation (id excluded):
# 4. Area first
Update the class Rectangle by adding the public method def area(self): that returns the area value of the Rectangle instance.
# 5. Display #0
Update the class Rectangle by adding the public method def display(self): that prints in stdout the Rectangle instance with the character # - you don’t need to handle x and y here.
# 6. str
Update the class Rectangle by overriding the str method so that it returns [Rectangle] () / - /
# 7. Display #1
Update the class Rectangle by improving the public method def display(self): to print in stdout the Rectangle instance with the character # by taking care of x and y
# 8. Update 0
Update the class Rectangle by adding the public method def update(self, *args): that assigns an argument to each attribute:
# 13. Rectangle instance to dictionary representation
Update the class Rectangle by adding the public method def to_dictionary(self): that returns the dictionary representation of a Rectangle:
# 15. Dictionary to JSON string
JSON is one of the standard formats for sharing data representation.
# 16. JSON string to file
Update the class Base by adding the class method def save_to_file(cls, list_objs): that writes the JSON string representation of list_objs to a file:
# 18. Dictionary to Instance
Update the class Base by adding the class method def create(cls, **dictionary): that returns an instance with all attributes already set:
# 19. File to instances
Update the class Base by adding the class method def load_from_file(cls): that returns a list of instances:
Author
Darrence