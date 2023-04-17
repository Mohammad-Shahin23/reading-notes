# Class Reading 07 

## Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
   The concept of variable scope in Python refers to the area or region of the code where a variable can be accessed.
   In Python, there are two types of variable scopes: local and global. Local variables are defined within a function and can only be accessed within that function, whereas global variables are defined outside of a function and can be accessed from any part of the code.
   ### Example
   def function():
    x = 10     # local variable
    print(x)

    x = 5    # global variable
    function()
    print(x)


## How do the global and nonlocal keywords work in Python, and in what situations might you use them?

    The global and nonlocal keywords in Python are used to access global and non-local variables respectively from within a function.
    The global keyword is used to declare that a variable is a global variable, meaning it can be accessed from anywhere in the code. 
    For example, if a function needs to access a global variable defined outside of the function, the global keyword is used to indicate this.



## In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
   Big O notation is a mathematical notation used to describe the performance of an algorithm in terms of its time and space complexity.

## Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
    To simulate a dice roll using Python, we can use the random module. The random.randint(a, b) function generates a random integer between a and b (inclusive). To simulate a dice roll, we can generate a random integer between 1 and 6.

    To calculate the probability of rolling a specific number over a large number of trials, we can simulate the dice roll multiple times and count the number of times the desired number is rolled.
     
    We can then divide the number of times the desired number was rolled by the total number of rolls to get the probability.

