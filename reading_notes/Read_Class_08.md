# Class Reading 08 

## What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
   List comprehension differs from using a for loop to create a list in that it is more concise and often easier to read. It also has the added benefit of being faster and more memory-efficient for larger lists.
   
   ### Example
   numbers = [1, 2, 3, 4, 5]
    squares = [num**2 for num in numbers]
    print(squares)


## What is a decorator in Python?
A decorator in Python is a special kind of function that can be used to modify or enhance the behavior of other functions or classes. Decorators allow you to add functionality to existing code without having to modify that code directly.


 ### Example
    def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

    @my_decorator
    def say_hello():
        print("Hello!")

    say_hello()




## Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
   Decorators are a way to modify or enhance the behavior of existing functions or classes in Python, without changing their source code. 
   They allow you to add functionality to a function or class by wrapping it with another function that provides the additional behavior. 
   Decorators are themselves functions that take another function as input and return a new function.
   ### Example:
    def log_decorator(func):
    def wrapper(*args, **kwargs):
        print(f"Called function {func.__name__} with args: {args}, kwargs: {kwargs}")
        result = func(*args, **kwargs)
        print(f"Function {func.__name__} returned: {result}")
        return result
    return wrapper

    @log_decorator
    def add(x, y):
        return x + y

    result = add(2, 3)
    print(result)


