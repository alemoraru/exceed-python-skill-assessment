# Programming Skill Level MCQ Survey - Version 5

This survey is designed to assess your understanding and ability to identify, understand, and resolve common programming
errors across general and Python-specific contexts. Each question has only one correct answer.

## Pre-Examination
---

**How would you describe your experience in Python**

- I have no previous experience in Python
- Focusing on syntax & basics, relying on tutorials, lacking real-world project experience
- Practical experience, small projects or assignments. Grasping basic concepts, and troubleshooting independently.
- Experience with projects. Able to independently plan and execute tasks, proficient with Python's libraries.
- Experience in complex projects. Deep understanding, ability to conciously resolve difficult problems.
- Significant experience in larger complex programs. Solves complex problems effortlessly and subconsciously.

### General Programming Error Understanding
---

1. **What is the main purpose of a programming error message?**
    - A) To provide a warning about potential issues in the code
    - B) To indicate that the code has been successfully compiled
    - C) To notify the programmer that something is wrong in the code during compilation or execution
    - D) To suggest optimizations for better performance

   Correct Answer: C)

2. **Which of the following statements best describes what a syntax error indicates?**
    - A) The program logic is incorrect
    - B) There's an issue with variable naming conventions
    - C) The code does not conform to the rules of the language grammar
    - D) A file or resource cannot be found

   Correct Answer: C)

3. **What typically triggers a runtime error?**
    - A) Improper indentation in Python
    - B) Trying to divide by zero
    - C) Using an undefined variable name
    - D) Missing semicolons at the end of statements (in languages that require them)

   Correct Answer: B)

4. **What are semantic/logical errors?**
    - A) Errors detected by the compiler during code compilation
    - B) Errors where the program runs without errors but produces undesirable results
    - C) Errors due to syntax mistakes like missing parentheses
    - D) Errors related to file system permissions

   Correct Answer: B)

5. **What does a "type mismatch" error usually indicate?**
    - A) The function has too many return statements
    - B) A variable is being used before it's initialized
    - C) A value is assigned or passed that doesn’t match the expected data type
    - D) The code is missing a necessary import or include

   Correct Answer: C)

6. **What distinguishes a compilation error from an interpretation error?**
    - A) Compilation errors occur at runtime, interpretation errors do not
    - B) Compilation errors only occur in dynamically typed languages
    - C) Compilation errors occur before execution; interpretation errors may happen during execution
    - D) They are the same; the terms are interchangeable

   Correct Answer: C)

7. **Why might a program fail to compile even if the logic seems correct?**
    - A) The output is not what was expected
    - B) The program uses inefficient algorithms
    - C) The code violates the language's grammar rules
    - D) The program takes too long to execute

   Correct Answer: C)

### Python-Specific General Error Understanding
---

8. **Which error message typically indicates that a Python variable has not been defined?**
    - A) `SyntaxError: invalid syntax`
    - B) `NameError: name 'x' is not defined`
    - C) `TypeError: unsupported operand type(s)`
    - D) `IndentationError: expected an indented block`

   Correct Answer: B)

9. **What does the following Python error message indicate?**
   ```python
   TypeError: can only concatenate str (not "int") to str
   ```
    - A) The code tries to open a file that doesn't exist
    - B) Two incompatible types are being combined without explicit conversion
    - C) A variable is used before it has been assigned a value
    - D) There's an issue with function call syntax

   Correct Answer: B)

10. **What does the following Python error message indicate?**
   ```python
   IndexError: list index out of range
   ```
- A) The code attempts to access an element outside the boundaries of a list
- B) An invalid data type is being used in a string formatting operation
- C) The code does not have enough elements in a list to perform the operation
- D) A syntax error related to list comprehension

Correct Answer: A)

11. **What does the following Python error message indicate?**
    ```python
    AttributeError: 'int' object has no attribute 'append'
    ```
    - A) You're trying to use a list method on a variable that holds an integer
    - B) You're trying to index an integer like a list
    - C) You're calling a method that belongs to strings, but on an integer
    - D) You're trying to use a method on the wrong object type

    Correct Answer: A)

12. **What does the following Python error message indicate?**
    ```python
    ZeroDivisionError: division by zero
    ```
    - A) The code is trying to divide a number by zero
    - B) The code is trying to concatenate incompatible types
    - C) The code is trying to divide zero by a number
    - D) The code is missing a return statement

    Correct Answer: A)

13. **What does the following Python error message indicate?**
    ```python
    IndentationError: unexpected indent
    ```
    - A) The code has an extra indentation where none was expected
    - B) A block of code is missing a required indentation
    - C) A block of code uses inconsistent indentation (spaces vs. tabs)
    - D) A function was called before it was defined

    Correct Answer: A)

14. **What does the following Python error message indicate?**
    ```python
    TypeError: 'int' object is not subscriptable
    ```
    - A) You're trying to loop through an integer as if it's a list or iterable
    - B) You’re trying to call an integer as if it were a function
    - C) You tried to access an element of an integer using square brackets
    - D) You passed an integer to a method that expects a string

    Correct Answer: C)

### Error Identification
---

15. **Given the code snippet below, identify the line where an error occurs and why.**

    ```python
    1: def greet(name):
    2:     print("Hello, " + name)
    3: 
    4: greet(John)
    ```

    - A) Line 1: Function definition error
    - B) Line 2: Concatenation type mismatch
    - C) Line 4: `John` is not defined (Name error)
    - D) Line 4: John is treated as a function but is not defined

    Correct Answer: C)

16. **The following code snippet is known to include an issue that will cause an error when executed. Choose the option
    that correctly identifies the type of error that will be produced.**

   ```python
   x = "100a"
y = int(x)
   ```

- A) `ValueError: invalid literal for int() with base 10: '100a'`
- B) `TypeError: int() cannot convert letters to integers`
- C) `SyntaxError: invalid syntax`
- D) `NameError: name 'x' is not defined`

Correct Answer: A)

17. **The following code snippet is known to include an issue that will cause an error when run. Identify the line and
    type of error that will be produced when the code is executed.**

    ```python
    1: x = 10
    2: if x > 5
    3:     print("x is greater than 5")
    ```

    - A) Line 1: `NameError` due to undefined variable
    - B) Line 2: `SyntaxError` due to missing colon
    - C) Line 2: SyntaxError due to extra comparison
    - D) Line 3: `IndentationError` due to wrong indent

    Correct Answer: B)

18. **Given the following code snippet, what is the most likely error message one will receive when trying to execute
    it.**

    ```python
    x = [1, 2, 3]
    print(x[3])
    ```  
    - A) `IndexError: list index out of range`
    - B) `TypeError: list index must be an integer`
    - C) `TypeError: 'list' object is not callable`
    - D) `NameError: name 'x' is not defined`

    Correct Answer: A)

19. **Read the code snippet below, and identify the error that is present.**

    ```python
    data = {"key": "value"
    print(data["key"])
    ```  

    - A) `KeyError: 'key'`
    - B) `SyntaxError: unexpected EOF while parsing`
    - C) `SyntaxError: missing colon in dictionary key-value pair`
    - D) `TypeError: 'dict' object is not callable`

    Correct Answer: B)

20. **Given the following code snippet, what is the most likely error message one will receive when trying to execute
    it?**

    ```python
    x = "5"
    y = 3
    print(x - y)
    ```  

    - A) `TypeError: unsupported operand type(s) for -: 'str' and 'int'`
    - B) `TypeError: cannot perform subtraction between string and number`
    - C) `ValueError: cannot subtract string from int`
    - D) `IndexError: invalid index operation`

    Correct Answer: A)

21. **The following code snippet produces an error and does not execute correctly. Pick the answer that represents the
    most likely error.**

    ```python
    def foo():
        print("Starting function")
        x = 5
        if x > 3:
            print("x is greater than 3")
          print("x is not greater than 3")
    foo()
    ```

    - A) `IndentationError: unindent does not match any outer indentation level.`
    - B) `IndentationError: expected an indented block after 'if' statement`
    - C) `NameError: x is not defined`
    - D) `TypeError: unsupported operand type(s)`

    Correct Answer: A)

### Error Resolution
---

22. **The following code snippet is known to include an issue that will cause an error when executed. Choose the option
    that correctly resolves the error while maintaining the desired result.**

    ```python
    # Print all non-negative integers until 5 included 
    for i in range(6)
        print(i)
    ```

    - A) Remove the `for` keyword
    - B) Add a colon (i.e. `:`) at the end of the `for` line
    - C) Replace `range(6)` with `[0,5]`
    - D) Add an `if` statement to check for non-negative integers

    Correct Answer: B)

23. **The following code produces an error when executed. Which change would fix the error while preserving the intended
    behavior described in the docstrings?**

    ```python
    def sum_list(lst):
        """
        This function computes the sum of a list of numbers.
        """
        total = 0
        for i in lst:
            total += i
        return total

    # Sum of the list must be 10
    print(sum_list([1, 2, "3", 4]))
    ```

    - A) Remove the string `"3"` from the list
    - B) Convert each element to `int` before performing addition
    - C) Use a try block around the loop to skip the error
    - D) Remove the for loop and use `sum(lst)` instead

    Correct Answer: B)

24. **The following code produces an error when executed. Which change would fix the error while preserving the intended
    behavior described in the docstrings?**

    ```python
    def power(base, exponent):
        """
        This function computes the power of a number.
        If an exponent is not provided, we assume it to be 0.
        """
        return base ** exponent

    print(power(2))
    ```

    - A) Remove the exponent parameter from the function definition
    - B) Provide a default value for the exponent
    - C) Rename the function to avoid conflicts with built-ins
    - D) Change the operator to multiplication (i.e. `*`) instead of exponentiation (i.e. `**`)

    Correct Answer: B)

25. **The `countdown` function below sometimes results in an error when called with certain inputs. Which change would
    fix the error while preserving the function’s intended behavior, as described in the docstrings?**

    ```python
    def countdown(n):
        """
        This function recursively counts down from n to 0.
        """
        if n == 0:
            print("Blast off!")
        else:
            print(n)
            countdown(n - 1)

    countdown(-3)
    ```

    - A) Change the base case to `if n <= 0:`
    - B) Add a default value for `n`
    - C) Change the `else` statement to an `elif` statement
    - D) Replace recursion with an iterative `for` loop approach

    Correct Answer: A)

26. **The following Python code does not correctly print the double of a number. Choose the option that best resolves
    the logical error while maintaining the intended functionality.**

    ```python
    double = lambda x: x * 2
    print(double)
    ```

    - A) Surround `x * 2` with `print()`
    - B) Replace `lambda` with `def` to make it work
    - C) Call the `double` function by adding parentheses with an argument
    - D) Remove the `lambda` and just write `x * 2`

    Correct Answer: C)

27. **The `first_char` function below sometimes results in an error when called with certain inputs. Which change would
    fix the error while preserving the function’s intended behavior, as described in the docstrings?**

    ```python
    def first_char(s):
        """
        This function returns the first character of a string.
        If the string is empty or None, it returns None.
        """
        if len(s) > 0:
            return s[0]
        else:
            return None

    print(first_char(None))
    ```

    - A) Convert `None` to an empty string before passing it to the function
    - B) Check if `s` is not `None` before calling `len()`
    - C) Replace `None` with an empty string in the function
    - D) Always return `s[0]` without checking the length

    Correct Answer: B)

28. **The code below is intended to apply a square function to each number within a list, but it raises an error. Choose
    the correct fix that maintains the logic.**

    ```python
    nums = [1, 2, 3]
    squared = map(lambda x: x**2, nums)
    print(squared[0])
    ```

    - A) Use `list(squared)[0]` to access the first value
    - B) Replace map with a list comprehension
    - C) Use `squared = lambda x: x**2`
    - D) Change `lambda x: x**2` to `lambda x: pow(x, 2)`

    Correct Answer: A)

### Code Reading / Understanding
---

29. **Consider the code snippet below. What option correctly explains the behavior of the following program?**

    ```python
    x = int("0")
    if x != 0 and (10 / x) > 2:
        print("Division succeeded")
    print("Could not divide by " + str(x))
    ```

    - A) The code contains a syntax error and won't run properly
    - B) The condition should use `or` instead of `and`, because `and` forces evaluation of both sides of the condition,
      which throws an error
    - C) Division by zero error is avoided due to short-circuit logic
    - D) The code contains a `TypeError` as `"0"` can be ambiguously interpreted to different primitive types

    Correct Answer: C)

30. **Read the code snippet below and identify which code line is logically wrong when computing the area of a
    rectangle.**

    ```python
    1: def area_rectangle(length, width):
    2:     """Compute the area of a rectangle and print it."""
    3:     area = length * width
    4:     print("The area is", area) 
    5: area_rectangle(5, 10)
    ```

    - A) Line 2 – Incorrect docstring format
    - B) Line 3 – Incorrect multiplication operator
    - C) Line 4 – Print statement formatting error
    - D) No line; the code is logically correct

    Correct Answer: D)

31. **Read the code snippet below and identify what the expected output is when the code is executed.**

    ```python
    def get_greeting():
        print("Hello, World!")
        
    message = get_greeting()
    print(message)
    ```

    - A) `Hello, World!` followed by `None`
    - B) An error because the function returns nothing
    - C) Two lines of `Hello, World!`
    - D) Only `Hello, World!`

    Correct Answer: A)

32. **Read the code snippet below and identify what the expected output is when the code is executed.**

    ```python
    x = 8
    y = 3

    result = x == y * 2 + 2
    print(result)
    ```

    - A) `True`
    - B) `False`
    - C) An error, because `==` is incorrectly used instead of `=`
    - D) Nothing, as the code contains an error

    Correct Answer: A)

33. **Read the code snippet below and identify what the expected output is when the code is executed.**

    ```python
    a = 5
    b = 10

    if a == b:
        print("a is equal to b")
    elif b == a:
        print("b is equal to a")
    else:
        print("a is not equal to b")
    ```

    - A) `a is equal to b`
    - B) `b is equal to a`
    - C) `a is not equal to b`
    - D) Nothing, as the code contains an error

    Correct Answer: C)

34. **Read the code snippet below and identify what the expected output is when the code is executed.**

    ```python
    a = True or 3/0
    print(a)
    ```

    - A) `True`
    - B) An error message related to division by zero
    - C) `False` (after displaying an error message)
    - D) Nothing, as the first operand in the or statement is already `True`

    Correct Answer: A)

35. **Read the code snippet below and identify what the expected output is when the code is executed.**

    ```python
    a = False
    b = True
    if a or b and not a:
        print("Condition met")
    else:
        print("Condition not met")
    ```

    - A) `Condition met`
    - B) `Condition not met`
    - C) No output, since there is an error with the logical operators
    - D) No errors, but also no output

    Correct Answer: A)

### Error Message Comprehension
---

36. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 3, in <module>
        print(elements[5])
    IndexError: list index out of range
    ```

    - A) The list `elements` has fewer than 6 elements
    - B) The list `elements` is not defined
    - C) The list is indexed starting at 1, so 5 is out of range
    - D) The list is empty and cannot be printed

    Correct Answer: A)

37. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 1, in <module>
        def my_function()
        ^
    SyntaxError: invalid syntax
    ```

    - A) The function definition is missing a colon at the end
    - B) The function is missing a return statement
    - C) There’s a problem with the indentation of the function
    - D) The variable `my_function` hasn’t been assigned a value

    Correct Answer: A)

38. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 4, in <module>
        print(x)
    NameError: name 'x' is not defined
    ```

    - A) The variable `x` hasn’t been initialized or declared before being used
    - B) The variable `x` has the wrong type assigned to it
    - C) The code is attempting to access a variable from another function’s scope
    - D) The print statement must reference an index of `x`

    Correct Answer: A)

39. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 2, in <module>
        int("one")
    ValueError: invalid literal for int() with base 10: 'one'
    ```

    - A) You cannot convert variables inside the `int()` function.
    - B) The string `"one"` is too long to be converted to an integer.
    - C) The `int()` function can only be used on floating point numbers.
    - D) The code is trying to convert a string that is not a valid number into an integer.

    Correct Answer: D)

40. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 5, in <module>
        open("file.txt", "r")
    FileNotFoundError: [Errno 2] No such file or directory: 'file.txt'
    ```

    - A) The file is open in another program and cannot be accessed
    - B) The file `file.txt` does not exist in the current directory
    - C) The code is trying to write to a file that is set to read-only
    - D) There is a syntax error when using the `open()` function to read `file.txt`

    Correct Answer: B)

41. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 3, in <module>
        my_list.remove(10)
    ValueError: list.remove(x): x not in list
    ```

    - A) The list `my_list` is empty, therefore nothing can be removed
    - B) The value of `x` is not found in `my_list`, so it can't be removed
    - C) You must assign the result of `.remove()` to a new variable
    - D) The value of `10` is not found in `my_list`, so it can't be removed

    Correct Answer: D)

42. **Based only on the error message below, which option best explains the cause of the error?**

    ```
    Traceback (most recent call last):
    File "main.py", line 3, in <module>
        data = {"name": "Alice", "age": 30}
        print(data["email"])
    KeyError: 'email'
    ```

    - A) The dictionary `data` is not defined properly
    - B) The code is trying to access a key `'email'` that doesn't exist in the dictionary
    - C) The key `'email'` needs to be declared as a variable first
    - D) Dictionaries cannot store strings as keys

    Correct Answer: B)

### Natural Language Scenarios

43. **You write a program to calculate the average of three numbers entered by the user. The code runs without crashing,
    but the result is slightly incorrect each time. What is the MOST likely cause for this, given the limited context?**

    - A) A `SyntaxError` caused the wrong result to be stored.
    - B) A `TypeError` occurred when dividing numbers.
    - C) A logic error in how the average is computed.
    - D) An `IndexError` occurred due to incorrect list indexing.

    Correct Answer: C)

44. **You're debugging a program that initially throws a `NameError`. You fix it, but the same error pops up again after
    later code changes in subsequent code runs. What is the MOST likely explanation for this, given the limited context?
    **

    - A) Your fix introduced a dependency that wasn't fully resolved elsewhere in the code.
    - B) `NameError`s will reappear unless the variable type is explicitly declared.
    - C) A similar issue is occurring in a different scope or function that wasn't originally part of the fix.
    - D) `KeyError` and `NameError` are essentially interchangeable and often happen together.

    Correct Answer: C)

45. **You're combining a number and a string using the `+` operator in Python, but it throws a `TypeError`. What concept
    do you need to understand to resolve this?**

    - A) How Python prioritizes operators in mixed expressions.
    - B) How Python distinguishes between different data types and converts them.
    - C) The correct way to define a function that adds strings and numbers.
    - D) The behavior of zero division and its impact on type operations.

    Correct Answer: B)

46. **You write a function to calculate the average of a list of numbers. The function returns the correct result when
    you use it with small lists, but it crashes with an `IndexError` when used on a very large list. What is the MOST
    likely reason for this, given the limited context?**

    - A) Python’s internal list functions don’t support large datasets by default.
    - B) The function contains assumptions about list size or structure that don’t hold for all inputs.
    - C) An `IndexError` indicates a problem with your computer's memory allocation.
    - D) The error arises from recursion depth, not from list indexing directly.

    Correct Answer: B)

47. **You're writing a program that uses a dictionary to store user preferences. You try to access a key that you _know_
    exists in the dictionary, but your code throws a `KeyError`. What is the MOST likely reason for this, given the
    limited context?**

    - A) The key might have been altered or removed elsewhere in the code
    - B) The key is actually a string, but you’re trying to access it with an integer
    - C) There’s a typo in the key you are trying to access (e.g., `"User"` vs `"user"`), or the case sensitivity is
      different than expected
    - D) Dictionaries can sometimes fail to locate keys due to internal hashing bugs or collisions

    Correct Answer: C)

48. **You're iterating through a list of strings and calling a method on each, but receive an `AttributeError`. What is
    the MOST likely reason for this, given the limited context?**

    - A) The `for` loop is incorrectly structured and is causing unexpected behavior
    - B) You're attempting to access or call something (a method or attribute) that isn't available for the type of
      object you’re working with
    - C) The strings in your list are actually integers disguised as strings
    - D) `AttributeError` only occurs when using recursion

    Correct Answer: B)

49. **You’re writing a program that uses recursion to calculate the factorial of a number. The program works correctly
    for small numbers, but crashes with a `RecursionError` on large inputs. What’s the MOST likely reason for this,
    given the limited context?**

    - A) `RecursionError` is usually caused by defining `for` loops incorrectly
    - B) The base case is incorrectly written, causing infinite recursion
    - C) Python's recursion depth limit has been exceeded, meaning the function called itself too many times
    - D) Factorial can’t be computed for large numbers in Python due to memory limits

    Correct Answer: C)

### Miscellanous Questions - Various Complexity & Scope
---

50. **Review the function below and determine the logical error causing an incorrect result, if any.**

    ```python
    def find_max(numbers):
        max_val = 0
        for num in numbers:
            if num > max_val:
                max_val = num
        return max_val

    result = find_max([-10, -5, -3])
    ```

    - A) It incorrectly returns the wrong number instead of the maximum value due to improper initialization of
      `max_val`
    - B) The for-loop is structured incorrectly as it does not iterate through all of the array's values
    - C) It raises an exception due to negative values being present in the list
    - D) There is no logical error present; the code correctly assigns the value of `-3` to the `result` variable

    Correct Answer: A)

51. **Examine the following `Rectangle` class definition. What is the issue in this code, if any?**

    ```python
    class Rectangle:
        def __init__(self, width, height):
            self.width = width
            self.height = height
            
        def area(self):
            return width * height

    rect = Rectangle(3, 4)
    print(rect.area())
    ```  

    - A) The attributes `width` and `height` are not prefixed with `self.` inside the `area` method
    - B) The `area` method is missing the `self` parameter in its definition
    - C) The call to `Rectangle(3, 4)` is invalid because the constructor expects 3 arguments, including `self`
    - D) There is no error; the code is both syntactically and semantically correct

    Correct Answer: A)

52. **Read the code snippet below. The `process_data` function can sometimes encounter an error during execution. Which
    option correctly identifies the cause and suggests a valid fix?**

    ```python
    def process_data(data_list):
        total = 0
        for item in data_list:
            try:
                total += int(item)
            except ValueError:
                print(f"Skipping non-integer value: {item}")
        
        average = total / len(data_list)
        return average

    # Example usage
    data = ["10", "20", "thirty", "", "40"]
    result = process_data(data)
    print("The average is:", result)
    ```
    - A) Remove `try-except` block; it's unnecessary with proper input validation
    - B) Convert empty strings to zero before adding to `total`
    - C) Ensure division by a non-zero number by checking if `data_list` is not empty before calculating the average
    - D) All of the above are valid fixes

    Correct Answer: C)

53. **Analyze the code below and identify the error that will occur when it is executed.**

    ```python
    def get_value(d, key):
        return d[key]

    d = {"a": 1, "b": 2}
    print(get_value(d, "c"))
    ```  

    - A) `KeyError: 'c'`
    - B) `SyntaxError: invalid syntax`
    - C) `NameError: name 'd' is not defined`
    - D) `TypeError: 'dict' object is not callable`

    Correct Answer: A)

54. **In the code snippet below, what is the mistake that prevents the correct evaluation of the condition?**

    ```python
    x = "10"
    if x = 10:
        print("x is ten")
    ```

    - A) The condition should be wrapped in parentheses
    - B) The print statement is incorrect
    - C) The variable `x` is compared to an integer instead of a string
    - D) Assignment operator is used insted of comparison operator

    Correct Answer: D)

55. **The code snippet below raises an error and does not compute the sum of the list correctly. Choose the option that
    both fixes the error and ensures the correct sum (10) is printed on line 6.**

    ```python
    def sum_list(lst):
        total = 0
        for i in lst:
           total += i
        return total
    print(sum_list([1, 2, "3", 4]))
    ```

    - A) Remove the string `"3"` from the list
    - B) Cast each element to an `int` before addition
    - C) Change the function name to `total_sum`
    - D) Remove the `for` loop

    Correct Answer: B)

56. **Examine the following code. What type of error will occur when the code is executed?**

    ```python
    class MyClass:
        def __init__(self, value):
            self.value = value
        def display():
            print(self.value)

    obj = MyClass(10)
    obj.display()
    ```  

    - A) `SyntaxError: invalid syntax`
    - B) `NameError: name 'self' is not defined`
    - C) `AttributeError: 'MyClass' object has no attribute 'display'`
    - D) `TypeError: MyClass.display() takes 0 positional arguments but 1 was given`

    Correct Answer: D)

### Post-Examination
---

**Take a moment to reflect on your responses. Approximately how many of the 16 questions do you think you got right?
Please provide your best guess as a number from 0 to 56.**

Answer: 