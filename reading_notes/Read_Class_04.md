# Class Reading 04 

## 1.What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?

    Classes are defined using the "class" keyword, whereas objects are created using the class name followed by parentheses (e.g. my_object = MyClass()).
    Classes can have class-level attributes and methods, which are shared among all instances of the class, whereas objects have instance-level attributes and methods that are specific to each object.
    Classes can inherit attributes and methods from other classes, whereas objects do not have this capability.

## 2. Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?

   Recursion is a technique in programming where a function calls itself one or more times in order to solve a problem. A function that uses recursion is called a recursive function.

   best practices to follow when implementing a recursive function:
   
        1-   Always define a base case that will eventually be reached by the function and return a value without calling itself.
        2-Make sure each recursive call moves the function closer to the base case.
        3-Use a debugger or print statements to help you understand the flow of execution and identify any issues.
        4-Avoid recursion if there is a simpler, iterative solution


## 3.What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.

    Pytest fixtures serve as a means to establish a consistent starting point for a group of tests. These fixtures enable the creation of prerequisites for tests, provision of test data, or generation of objects that are required by multiple tests. The "@pytest.fixture" decorator is employed to define fixtures.

    Code coverage refers to the proportion of your code that is executed during testing. It assists in recognizing any untested code and can boost the overall quality of your project.



## Things I want to know more about
    1-Test-Driven Development (TDD)
    2-Mocking and patching
    3-Test automation frameworks