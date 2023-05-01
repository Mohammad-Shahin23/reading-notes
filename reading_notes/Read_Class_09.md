# Class Reading 09 

## What is the purpose of dunder methods in Python? Provide an example of a commonly used dunder method.
   Dunder methods are special methods in Python that have a specific naming convention and allow us to define specific behaviors for built-in operators or syntax. A commonly used dunder method is __str__() which returns a string representation of an object.
   
   ### Example
   class MyClass:
    def __init__(self, x):
        self.x = x
    
    def __str__(self):
        return f"MyClass object with x = {self.x}"
    
    obj = MyClass(5)
    print(obj)  


## In the video “AI Guru makes $238,800 with misleading paid course,” what was the main ethical issue raised concerning the use of developers’ work, and how might this have been avoided?
The main ethical issue raised in the video "AI Guru makes $238,800 with misleading paid course" concerned the use of developers' work without proper attribution or compensation, violating the principles of open-source software. To avoid this, developers should follow the guidelines and licenses of open-source projects and give proper attribution to the original authors.






## Describe the Python statistics module and give an example of a function within the module that can be used to perform a common statistical operation.
   The Python statistics module is a built-in module providing functions for statistical analysis. The median() function within the module takes a list of numbers as input and returns the median value. Other functions in the module include mean, mode, variance, standard deviation, and correlation coefficient.
