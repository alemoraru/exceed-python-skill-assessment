# Programming Skill Level MCQ Survey - Version 4

This survey is designed to assess your understanding and ability to identify, understand, and resolve common programming errors across general and Python-specific contexts. Each question has only one correct answer.

### Pre-Examination
---

**How would you describe your experience in Python**

- I have no previous experience in Python
- Focusing on syntax & basics, relying on tutorials, lacking real-world project experience
- Practical experience, small projects or assignments. Grasping basic concepts, and troubleshooting independently.
- Experience with projects. Able to independently plan and execute tasks, proficient with Python's libraries.
- Experience in complex projects. Deep understanding, ability to conciously resolve difficult problems.
- Significant experience in larger complex programs. Solves complex problems effortlessly and subconsciously. 

### General Compiler Error Understanding
---

1. **Which of the following statements best describes what a syntax error indicates?**
   - A) The program logic is incorrect.
   - B) There's an issue with variable naming conventions.
   - C) The code does not conform to the rules of the language grammar.
   - D) A file or resource cannot be found.

2. **What typically triggers a runtime error?**
   - A) Improper indentation in Python.
   - B) Trying to divide by zero.
   - C) Using an undefined variable name.
   - D) Missing semicolons at the end of statements (in languages that require them).

3. **Semantic/Logical errors are:**
   - A) Errors detected by the compiler during code compilation.
   - B) Errors where the program runs but produces incorrect results.
   - C) Errors due to syntax mistakes like missing parentheses.
   - D) Errors related to file system permissions.

### Python-Specific General Error Understanding
---

4. **Which error message indicates that a variable has not been defined?**
   - A) `SyntaxError: invalid syntax`
   - B) `NameError: name 'x' is not defined`
   - C) `TypeError: unsupported operand type(s)`
   - D) `IndentationError: expected an indented block`

5. **In Python, what does the following error message suggest?**
   ```python
   TypeError: can only concatenate str (not "int") to str
   ```
   - A) The code tries to open a file that doesn't exist.
   - B) Two incompatible types are being combined without explicit conversion.
   - C) A variable is used before it has been assigned a value.
   - D) There's an issue with function call syntax.

6. **What does the following error message indicate?**
   ```python
   IndexError: list index out of range
   ```
   - A) The code attempts to access an element outside the boundaries of a list.
   - B) An invalid data type is being used in a string formatting operation.
   - C) There's a problem with dictionary key access.
   - D) A syntax error related to list comprehension.

### Error Identification
---

7. **Given the code snippet below, identify the line where an error occurs and why.**

    ```python
    1: def greet(name):
    2:     print("Hello, " + name)
    3: 
    4: greet(John)
    ```

    - A) Line 1: Function definition error  
    - B) Line 2: Concatenation type mismatch  
    - C) Line 4: `John` is not defined (Name error)  
    - D) Line 4: Incorrect function call syntax  

8. **The following code snippet is known to include an issue that will cause an error when executed. Choose the option that correctly identifies the kind of error that will be produced.**

   ```python
   x = "100a"
   y = int(x)
   ```
   - A) `ValueError: invalid literal for int() with base 10: '100a'`  
   - B) `TypeError: unsupported operand type(s)`  
   - C) `SyntaxError: invalid syntax`  
   - D) `NameError: name 'x' is not defined` 

9. **The following code snippet is known to include an issue that will cause an error when run. Identify the line and type of error that will be produced when the code is executed.**

    ```python
    1: x = 10
    2: if x > 5
    3:     print("x is greater than 5")
    ```

    - A) Line 1: `NameError` due to undefined variable  
    - B) Line 2: `SyntaxError` due to missing colon
    - C) Line 2: `TypeError` due to improper comparison  
    - D) Line 3: `IndentationError` due to wrong indent

10. **Given the following code snippet, which is the most likely error message one will receive when trying to execute it.**

    ```python
    x = [1, 2, 3]
    print(x[3])
    ```  
    - A) `IndexError: list index out of range`  
    - B) `SyntaxError: invalid syntax`  
    - C) `TypeError: 'list' object is not callable`  
    - D) `NameError: name 'x' is not defined`  

11. **Given the following code snippet, which is the most likely error message one will receive when trying to execute it.**

    ```python
    def multiply(a, b):
        return a * b

    print(multiply(2))
    ``` 

    - A) `TypeError: multiply() missing 1 required positional argument: 'b'`
    - B) `NameError: multiply is not defined`  
    - C) `SyntaxError: invalid syntax` 
    - D) `ValueError: too many values to unpack`

12. **Read the code snippet below, and identify the error that is present.** 

    ```python
    data = {"key": "value"
    print(data["key"])
    ```  

    - A) `KeyError: 'key'` 
    - B) `SyntaxError: unexpected EOF while parsing (missing closing brace for the dictionary)`  
    - C) `NameError: data is not defined`  
    - D) `TypeError: 'dict' object is not callable`  

13. **Given the following code snippet, which is the most likely error message one will receive when trying to execute it.**

    ```python
    x = "100a"
    y = int(x)
    ```  

    - A) `ValueError: invalid literal for int() with base 10: '100a'`
    - B) `TypeError: unsupported operand type(s)`  
    - C) `SyntaxError: invalid syntax` 
    - D) `NameError: name 'x' is not defined`

14. **Given the following code snippet, which is the most likely error message one will receive when trying to execute it.**

    ```python
    x = "5"
    y = 3
    print(x - y)
    ```  

    - A) `TypeError: unsupported operand type(s) for -: 'str' and 'int'`  
    - B) `SyntaxError: invalid syntax`  
    - C) `ValueError: cannot subtract string from int`  
    - D) `IndexError: invalid index operation`   

15. **The following code snippet produces an error and does not compute the sum correctly. Pick the answer that fixes both the error and the logic.**

    ```python
    def foo():
        print("Starting function")
        x = 5
        if x > 3:
            print("x is greater than 3")
          print("This line is misindented")
    foo()
    ```

    - A) `IndentationError: unindent does not match any outer indentation level (on the misindented print statement).` 
    - B) `SyntaxError: invalid syntax`  
    - C) `NameError: x is not defined`  
    - D) `TypeError: unsupported operand type(s)`

16. **Read the code snippet below, abd identify the error and its location.**

    ```python
    def greet(name):
        print("Hello, " + name
        
    greet("Alice")
    ```  

    - A) `SyntaxError: unexpected EOF while parsing (missing closing parenthesis in the function).`  
    - B) `NameError: name 'name' is not defined.`  
    - C) `TypeError: unsupported operand type(s) for +.` 
    - D) `IndentationError: unexpected indent.`  

### Error Resolution
---

17. **The following code snippet is known to include an issue that will cause an error when executed. Choose the option that correctly resolves the error while maintaining the desired result.**

    ```python
    # Print all non-negative integers until 5 included 
    for i in range(5)
        print(i)
    ```

    - A) Remove the `for` keyword  
    - B) Add a colon (`:`) at the end of the `for` line  
    - C) Replace `range(5)` with `[0,5]`  
    - D) Indent the print statement further

18. **The following code snippet produces an error and does not compute the sum correctly. Pick the answer that fixes both the error and the logic.**

    ```python
    def sum_list(lst):
        total = 0
        for i in lst:
            total += i
        return total

    print(sum_list([1, 2, "3", 4]))
    ```

    - A) Remove the string `"3"` from the list  
    - B) Convert each element to int before addition  
    - C) Change the function name to `total_sum`  
    - D) Remove the for loop 

19. **The snippet below produces an error. Choose the option that correctly fixes the error.**

    ```python
    def power(base, exponent):
        return base ** exponent

    print(power(2))
    ```

    - A) Remove the exponent parameter from the function definition  
    - B) Provide a default value for the exponent  
    - C) Call the function with two arguments  
    - D) Change the operator to multiplication

### Code Reading / Understanding
---

20. **Consider the code below. Which option correctly explains the behavior of the following program?**

    ```python
    x = int("0")
    if x != 0 and (10 / x) > 2:
        print("Division succeeded")
    print("Could not divide by " + str(x))
    ```

    - A) The code contains a syntax error and won't run properly
    - B) The condition should use `or` instead of `and`, because `and` forces evaluation of both sides of the condition which throws an error.
    - C) Division by zero error is avoided due to short-circuit logic 
    - D) The code contains a `TypeError` as `"0"` can be ambigously interpreted to different primitive types.

21. **Analyze the code snippet below and determine whether it computes the area of a circle correctly.**

    ```python
    import math
    def area_circle(radius):
        return 2 * math.pi * radius ** 2

    print(area_circle(3))
    ```

    - A) Yes, it correctly computes the area  
    - B) No, the formula should not include multiplication by 2  
    - C) No, the exponent should be 1  
    - D) No, it should use integer division

22. **Read the code snippet below and identify which line is logically wrong when computing the area of a rectangle.**

    ```python
    1: def area_rectangle(length, width):
    2:     area = length * width
    3:     print("The area is", area)
    4: 
    5: area_rectangle(5, 10)
    ```

    - A) Line 1 – Function parameter issue  
    - B) Line 2 – Incorrect multiplication operator  
    - C) Line 3 – Print statement formatting error  
    - D) No line; the code is logically correct

23. **Read the code snippet below and identify what is the expected output when the code is executed.**

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

24. **Read the code snippet below and identify what will be printed by the code when executed.**

    ```python
    x = 8
    y = 3

    result = x == y * 2 + 2
    print(result)
    ```

    - A) `True`  
    - B) `False`  
    - C) An error because `==` should be `=`.  
    - D) Nothing, as the code contains an error.

25. **Read the code snippet below and identify what will be printed by the code when executed.**

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

    What will this code snippet output?

    - A) `a is equal to b`
    - B) `b is equal to a`  
    - C) `a is not equal to b`
    - D) Nothing, as the code contains an error.

26. **Read the code snippet below and identify what will be printed by the code when executed.**

    ```python
    a = True or 3/0
    print(a)
    ```

    - A) `True`
    - B) An error message related to division by zero
    - C) `False` (after displaying an error message)
    - D) Nothing, as the first operand in the or statement is already `True`

27. **Read the code snippet below and identify what will be printed by the code when executed.**

    ```python
    a = False and 3/0
    print(a)
    ```

    - A) `False`
    - B) An error message related to division by zero
    - C) `False` (after displaying an error message)
    - D) Nothing, as the first operand in the and statement is already `False`

28. **Read the code snippet below and identify what will be printed by the code when executed.**

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
    - C) Nothing, since there is an error with the logical operators  
    - D) No output

29. **What does the following code print when executed?**

    ```python
    def first():
        print("first")
        return True

    def second():
        print("second")
        return False

    if first() or second():
        print("result True")
    else:
        print("result False")
    ```

    - A) Prints `first` then `second` and `result True`  
    - B) Prints `first` and `result True` only  
    - C) Prints `second` then `result False`  
    - D) Prints `first`, `second`, and `result False`  

### Error Message Understanding
---

30. **Based solely on the error stack trace below, choose the best explanation of the error.**

    ```
    Traceback (most recent call last):
    File "main.py", line 3, in <module>
        print(my_list[5])
    IndexError: list index out of range
    ```

    - A) The list `my_list` has fewer than 6 elements  
    - B) The list `my_list` is not defined  
    - C) The list is empty  
    - D) The index should start at 1

31. **Based solely on the error stack trace below, choose the best explanation of the error.**

    ```python
    Traceback (most recent call last):
    File "main.py", line 2, in <module>
        result = "5" + 3
    TypeError: can only concatenate str (not "int") to str
    ```

    - A) The variable result is not defined.
    - B) An integer cannot be used as a string index.
    - C) You are trying to add an integer and a string together without proper conversion.
    - D) The code is attempting to divide by zero.

32. **Based solely on the error stack trace below, choose the best explanation of the error.**

    ```python
    Traceback (most recent call last):
    File "main.py", line 1, in <module>
        def my_function()
        ^
    SyntaxError: invalid syntax
    ```

    - A) The function definition is incomplete or has incorrect syntax.
    - B) The function is missing a return statement.
    - C) There's an issue with the indentation of the code block.
    - D) The variable my_function is not defined.

33. **Based solely on the error stack trace below, choose the best explanation of the error.**

    ```python
    Traceback (most recent call last):
    File "main.py", line 4, in <module>
        print(x)
    NameError: name 'x' is not defined
    ```

    - A) The variable x has been assigned the wrong data type.
    - B) The code is trying to print a list without specifying an index.
    - C) There's an issue with how the program handles exceptions.
    - D) The variable x hasn’t been initialized or declared before being used.

###  Natural Language Scenarios

34. **You write a program to calculate the average of three numbers entered by the user. The code runs without crashing, but the result is consistently off by a small amount. What is the most likely cause?**

    - A) A `SyntaxError` prevented correct calculation.
    - B) A `TypeError` occurred due to incompatible data types.
    - C) A logical error in the averaging formula.
    - D) An `IndexError` caused an out-of-bounds access.

35. **You are debugging a Python program that produces a NameError. You fix the immediate issue, but later find the same error reappears when you modify another part of the code. What is the MOST likely reason for this persistence?**

    - A) The initial fix was incomplete or introduced a new dependency.
    - B) `SyntaxError`s always reappear if not handled correctly.
    - C) `KeyError`s are inherently more difficult to resolve than `NameError`s.
    - D) `TypeError`s are less common in larger programs.

36. **You're trying to combine a number and a string using the + operator in Python, but you get a TypeError. What is the most important concept you need to understand to fix this?**

    - A) How to use parentheses for order of operations.
    - B) The difference between integers and strings, and how to convert between them.
    - C) How to handle division by zero errors.
    - D) How to define functions in Python.

37. **You write a function to calculate the average of a list of numbers. The function returns the correct result when you test it with small lists, but crashes with an `IndexError` when given a very large list. What is the MOST probable cause?**

    - A) Python's built-in averaging functions are inherently unstable for large datasets.
    - B) Your code likely assumes something about the structure or size of the input list that isn’t always true.
    - C) The `IndexError` indicates a problem with your computer's memory allocation.
    - D) Large lists automatically trigger different error handling in Python functions.

38. **You're writing a program that uses a dictionary to store user preferences.  You try to access a key that you know exists in the dictionary, but your code throws a KeyError. What is the MOST likely reason?**

    - A) The dictionary has been corrupted by another part of the program.
    - B) You're using the wrong data type for the key – it must be an integer.
    - C) There’s a typo in the key you are trying to access, or the case sensitivity is different than expected.
    - D) Dictionaries inherently throw `KeyError` exceptions more often than other data structures.

39. **You're using a for loop to iterate through a list of strings. Inside the loop, you try to call a method on each string that doesn’t exist.  You receive an `AttributeError`. What does this error indicate?**

    - A) The `for` loop is incorrectly structured and causing unexpected behavior.
    - B) You're attempting to access or call something (a method or attribute) that isn't available for the type of object you’re working with.
    - C) The strings in your list are actually integers disguised as strings.
    - D) `AttributeError`s only occur when using recursion.

40. **You’re writing a program that uses recursion to calculate the factorial of a number.  The program works correctly for small numbers but crashes with a `RecursionError` when you try to calculate the factorial of a larger number (e.g., 1000). What is the MOST likely reason?**

    - A) The factorial function itself has an inherent limitation on the size of numbers it can handle.
    - B) The program is running out of memory due to the large number being calculated.
    - C) Python's recursion depth limit has been exceeded, meaning the function called itself too many times.
    - D) `RecursionError`s are always caused by incorrect base cases in recursive functions.

### Miscellanous Questions - Various Complexity & Scope
---

41. **Given the code snippet below, identify the answer that best describes what error is present.**

    ```python
    def foo():
    print("Missing indentation")
    ```  

    - A) The print statement is not indented (it should be inside the function body).  
    - B) The function definition is missing a colon.  
    - C) The function name is misspelled.  
    - D) None of the above, the code contains no errors.

42. **Explain the error that is present in the code snippet below.**

    ```python
    from math import sin
    print(cos(0))
    ```  

    - A) `NameError: name 'cos' is not defined because only sin was imported.` 
    - B) `SyntaxError: invalid syntax` 
    - C) `TypeError: 'module' object is not callable`  
    - D) `AttributeError: module 'math' has no attribute 'cos'`

43. **What is the logical error in the code snippet below?**  

    ```python
    def find_max(numbers):
        max_val = 0
        for num in numbers:
            if num > max_val:
                max_val = num
        return max_val

    result = find_max([-10, -5, -3])
    ```

    - A) It incorrectly returns the wrong number instead of the maximum value due to improper initialization of `max_val`.  
    - B) The for-loop is structured incorrectly as it does not iterate through all of the array's values. 
    - C) It raises an exception due to negative values being present in the list.
    - D) There is no logical error present; the code correctly assigns the value of `-3` to the `result` variable.

44. **The following code snippet contains an error. Select the option that best selects why this error occurs.**

    ```python
    def subtract(a: str, b: str):
        return a - b

    print(subtract("10", "5"))
    ```  

    - A) Subtraction is not defined between string operands.  
    - B) The function `subtract()` is called with arguments of the wrong type.  
    - C) Both A and B.  
    - D) The function is missing a return statement.  

45. **Examine the following `Rectangle` class definition. Does it contain an error? If so, select the option that best describes the issue.**

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

    - A) The attributes `width` and `height` are not referenced with `self.` inside the method.  
    - B) The method should accept an extra parameter.  
    - C) When creating `rect`, it is mandatory to also provide `self`, since the `Rectangle`'s constructor accepts 3 arguments.
    - D) There is no error; the code is both syntactically and semantically correct.

46. **How can you fix the `TypeError` in the following code snippet?**

    ```python
    def concatenate_strings(str1, str2):
        return str1 + str2

    result = concatenate_strings("Hello", 42)
    print(result)
    ```

    - A) Change `str1` to an integer before concatenation.
    - B) Convert `str2` to a string using `str(str2)` before concatenation.
    - C) Use `+` operator only for numbers, not strings.
    - D) Replace `print(result)` with `return result`

47. **Identify the issue(s) in the following code snippet and how to resolve them:**

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

    data = ["10", "20", "thirty", "", "40"]
    result = process_data(data)
    print("The average is:", result)
    ```
    - A) Remove `try-except` block; it's unnecessary with proper input validation.
    - B) Convert empty strings to zero before adding to `total`.
    - C) Ensure division by a non-zero number by checking if `data_list` is not empty before calculating the average.
    - D) All of the above.

48. **Given the code snippet below, identify the option that best describes what type of error is present.**

    ```python
    def get_value(d, key):
        return d[key]

    d = {"a": 1, "b": 2}
    print(get_value(d, "c"))
    ```  

    - A) `KeyError: 'c' because the key does not exist in the dictionary.` 
    - B) `SyntaxError: invalid syntax`
    - C) `NameError: d is not defined`  
    - D) `TypeError: 'dict' object is not callable`

49. **In the snippet below, identify the mistake that prevents correct evaluation of the condition.**

    ```python
    x = 10
    if x = 10:
        print("x is ten")
    ```

    - A) The condition should be wrapped in parentheses  
    - B) The print statement is incorrect  
    - C) The variable `x` is not initialized 
    - D) The assignment operator `=` is used instead of `==`

50. **The following code snippet produces an error and does not compute the sum of a list of values correctly. Pick the answer that fixes both the error and the logic. The resulting sum that is printed must be 10.**

    ```python
    def sum_list(lst):
        total = 0
        for i in lst:
            total += i
        return total

    print(sum_list([1, 2, "3", 4]))
    ```

    - A) Remove the string `"3"` from the list  
    - B) Convert each element to `int` before addition  
    - C) Change the function name to `total_sum`  
    - D) Remove the `for` loop  

51. **You're seeing a NameError when you run this code. Which of these changes will correct the error and make sure the code snippet prints out the number 12?**

    ```python
    def multiply(a, b):
        return a * b

    print(multiplyy(3, 4))
    ```

    - A) Rename the function call to match the definition  
    - B) Import the `math` module before the method definition
    - C) Remove the function call  
    - D) Change the parameters to strings

52. **Given the code snippet below, identify the option that best describes what type of error is present.**

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

### Post-Examination
---

**Take a moment to reflect on your responses. Approximately how many of the 52 questions do you think you got right?  Please provide your best guess as a number from 0 to 52.**

Answer: 