# Class Reading 03

## 1- What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
    The 'with' statement in Python automatically manages resources like opening and closing files. It's used to ensure that the file is properly closed once the program is done reading or writing to it.

## 2- What is the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python, and when should each method be used?
    'read()' method reads the entire contents of a file and returns it as a single string. It's useful when you need to read the entire file at once. 'readline()' method, on the other hand, reads a single line of the file and returns it as a string. It's useful when you need to read a file line by line.

## 3- Can you briefly explain the concept of exception handling in Python, and how the ‘try’, ‘except’, and ‘finally’ blocks can be used to handle exceptions and ensure proper execution of code? Could you provide a simple example?
    Exception handling in Python is used to handle errors or exceptional events that may occur during the execution of a program. The 'try' block encloses the code that may raise an exception, while the 'except' block is used to handle the exception if it occurs. The 'finally' block is optional and is used to execute code that needs to run regardless of whether an exception was raised or not.
