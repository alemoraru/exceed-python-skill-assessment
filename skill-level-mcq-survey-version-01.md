# Programming Skill Level MCQ Survey - Version 1

This survey is designed to assess your understanding and ability to identify, understand, and resolve common programming errors across general and Python-specific contexts. The questions are divided into several sections, each focusing on a different aspect of error handling in programming:

* **General Compiler Error Understanding**: Test your knowledge about various types of compiler and runtime errors.
* **Python-Specific Error Understanding**: Evaluate your familiarity with typical error messages that arise specifically within the Python programming language.
* **Error Resolution and Debugging**: Check your ability to approach problem-solving when faced with an error message, including initial debugging steps and indirect causes for errors.
* **Error Identification**: Identify different types of errors in provided code snippets. These questions may vary in complexity from basic syntax issues to more nuanced logical errors.
* **Error Solving**: Determine the correct solutions or fixes for identified errors in given examples.

Your responses will help categorize your skill level into one of three tiers: Beginner, Intermediate, or Advanced (or two tiers if using a simplified scale). This survey aims not only to gauge your current proficiency but also to guide you towards areas that may benefit from further learning and practice.

### General Compiler Error Understanding

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

3. **Semantic errors are:**
   - A) Errors detected by the compiler during code compilation.
   - B) Logical errors where the program runs but produces incorrect results.
   - C) Errors due to syntax mistakes like missing parentheses.
   - D) Errors related to file system permissions.

### Python-Specific Error Understanding

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

### Error Resolution and Debugging

7. **Which approach should you take first when encountering an error message?**
   - A) Search online for the exact error message.
   - B) Review the line of code indicated in the error message.
   - C) Rewrite the entire block of code where the error occurs.
   - D) Comment out all parts of your program until it runs without errors.

8. **If an error message points to a specific line but you believe your syntax is correct, what might be another cause?**
   - A) The problem is elsewhere in the program affecting this line indirectly.
   - B) The compiler is malfunctioning and should be restarted.
   - C) You have misspelled 'Python' somewhere in your comments.
   - D) Syntax errors can never be correct.

9. **How would you address a `TypeError` when trying to concatenate a string with an integer in Python?**
   - A) Use a try-except block to catch the error at runtime.
   - B) Convert the integer to a string using `str()`.
   - C) Ignore the error; it will resolve itself during execution.
   - D) Use a different programming language that doesn’t have type restrictions.

### Error Identification

10. **Which error category does this situation fall under?**

 ```python
   print("The result is: " + 42)
   ```
   - A) SyntaxError
   - B) TypeError
   - C) NameError
   - D) Logical Error

11. **What type of error occurs if a program tries to use a variable that has not been defined?**
   - A) Runtime Error
   - B) Memory Leak
   - C) NameError
   - D) SyntaxError

12. **Determine the category of error for this issue:**
   ```python
   x = "10"
   y = int(x) / 0
   ```
   - A) Semantic Error
   - B) IndexError
   - C) Runtime Error
   - D) SyntaxError

13. **Identify any error present in the following Python code snippet:**
   ```python
   def greet(name):
       print("Hello, " + name)
   
   greet()
   ```
   - A) SyntaxError
   - B) NameError
   - C) TypeError
   - D) ValueError

### Error Identification (More Difficult)

14. **Identify any error present in the following code snippet:**
    ```python
    def calculate_area(radius):
        pi = 3.14159
        area = pi * (radius ** 2)
        return area

    def main():
        radius = float(input("Enter the radius of the circle: "))
        if radius < 0:
            print("The radius cannot be negative.")
        else:
            area = calculate_area(radius)
            print(f"The area of the circle is {area:.2f}")

    main()
    ```
   - A) SyntaxError
   - B) NameError
   - C) Logical Error
   - D) No Error

15. **Identify any error present in the following code snippet:**
    ```python
    def check_prime(number):
        if number <= 1:
            return False
        for i in range(2, int(number ** 0.5) + 1):
            if number % i == 0:
                return False
        return True

    def main():
        num = int(input("Enter a number to check if it's prime: "))
        if check_prime(num):
            print(f"{num} is a prime number.")
        else:
            print(f"{num} is not a prime number.")

    main()
    ```
   - A) SyntaxError
   - B) TypeError
   - C) Logical Error
   - D) No Error

16. **Identify any error present in the following code snippet:**
    ```python
    def divide_numbers(num1, num2):
        try:
            result = num1 / num2
            print(f"The result of dividing {num1} by {num2} is {result}.")
        except ZeroDivisionError:
            print("Cannot divide by zero!")

    def main():
        a = float(input("Enter the first number: "))
        b = int(input("Enter the second number: "))  # Note: different types used here
        divide_numbers(a, b)

    main()
    ```
   - A) Logical Error
   - B) SyntaxError
   - C) TypeError
   - D) No Error

### Error Solving

17. **Identify how to fix the syntax error in the following code snippet:**

    ```python
    def display_message(message):
        print("Message:", message)

    display_message("Hello, world!
    ```
    - A) Add an extra closing parenthesis to `print` function.
    - B) Remove the colon from the `display_message` function definition.
    - C) Add a missing closing parenthesis after `"Hello, world!"`
    - D) Replace `print` with `println`

18. **How can you fix the `NameError` in the following code snippet?**
    ```python
    def calculate_sum(a, b):
        result = a + b
        return result

    sum_value = calculateSum(5, 10)
    print("The sum is:", sum_value)
    ```
    - A) Rename the variable `sum_value`
    - B) Correct the function call to match the defined function name
    - C) Import a module that defines `calculateSum`
    - D) Add parentheses around `a + b` inside the function

19. **How can you fix the `TypeError` in the following code snippet?**
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

20. **Identify the primary issues in the following code snippet and how to resolve them:**
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

### Skill Level Assessment Scoreboard

**Using 3 Skill Levels**:

- **Beginner:** Struggles with identifying types of errors and understanding basic Python-specific messages. May not know initial debugging steps.
    * Threshold: 0-7 correct answers
  
- **Intermediate:** Understands error types and knows some specific fixes but may still be unsure about indirect causes or resolving complex issues.
    * Threshold: 8-14 correct answers

- **Advanced:** Accurately identifies and understands multiple error types, including semantic and runtime issues. Confident in troubleshooting and fixing errors with minimal external help.
    * Threshold: 15-20 correct answers

**Using 2 Skill Levels**:

- **Beginner:** Likely need foundational learning to handle fundamental programming tasks.
    * Threshold: 0-10 correct answers

- **Advanced:** Have demonstrated significant competency in handling and resolving typical errors efficiently.
    * Threshold: 11-20 correct answers
