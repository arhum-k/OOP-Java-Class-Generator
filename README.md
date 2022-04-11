# OOP-Java-Class-Generator

Why?

In my AP Computer Science A class, we do labs quite often, meaning we are frequently instructed to make new classes, each with a vast set of instance variables. For not only me, but my entire class, the process of writing each constructor, accessor/mutator method, and toString method is a hassle, so I created a class generator, that we could all use, that writes this code for us.

Input:
- Class name
- Instance variables (data type and name) of the class

Output:
- Generic code for the class
  - Declared instance variables
  - default constructor
  - parameterized constructor
  - accessor methods
  - mutator methods
  - toString method
-Button to copy the code to clipboard

To get the user's inputs, I used two text inputs where I then saved both results to a variable once the user clicked a button signaling that they are done. Based on the user's inputs, I created 2 methods that parsed the instance variable input to find the data type and variable name. In the function where I printed the entire output, I used the data type and variable name for the method headers and bodies each method. 


Try it out! - https://df1zc1.csb.app/
