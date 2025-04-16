# Programming Skill Level MCQ Survey - Version 3

This survey is designed to assess your understanding and ability to identify, understand, and resolve common programming errors across general and Python-specific contexts. The questions are divided into several sections (i.e. aspects), each focusing on a different aspect of error handling in programming:

### Aspect 1  
*Experienced programmers are significantly better at correctly finding and fixing bugs (though not necessarily faster).*

1. **Q1.1**  
   ```python
   def add_numbers(a, b):
       return a + b

   print(add_numbers(5, '3'))
   ```  
   **Which error message is produced?**  
   - A. TypeError: unsupported operand type(s) for +: 'int' and 'str'  
   - B. SyntaxError: invalid syntax  
   - C. ValueError: could not convert string to int  
   - D. IndexError: list index out of range  
   *(Correct Answer: A)*

2. **Q1.2**  
   ```python
   def foo():
   print("Missing indentation")
   ```  
   **Identify the error and its location.**  
   - A. The print statement is not indented (it should be inside the function body).  
   - B. The function definition is missing a colon.  
   - C. The function name is misspelled.  
   - D. None of the above  
   *(Correct Answer: A)*

3. **Q1.3**  
   ```python
   if True:
       print("Hello")
     print("World")
   ```  
   **Which error message does this produce?**  
   - A. IndentationError: unexpected indent  
   - B. IndentationError: unindent does not match any outer indentation level  
   - C. SyntaxError: invalid syntax  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: B)*

4. **Q1.4**  
   ```python
   def multiply(a, b):
       return a * b

   print(multiply(3))
   ```  
   **Where is the error located?**  
   - A. In the function definition (a parameter is missing there).  
   - B. In the function call (an argument is missing).  
   - C. In the return statement.  
   - D. In the print statement.  
   *(Correct Answer: B)*

5. **Q1.5**  
   ```python
   for i in range(5):
       print(i)
   print(j)
   ```  
   **Explain why the error “NameError: name 'j' is not defined” occurs.**  
   - A. The variable ‘j’ was never defined.  
   - B. The for-loop should have used ‘j’ as its iterator.  
   - C. The error is due to using a variable outside its scope.  
   - D. The error comes from a misspelled function name.  
   *(Correct Answer: A)*

---

### Aspect 2  
*Collected error messages in Python/Java follow a Zipf–Mandelbrot distribution; a few types (e.g. SyntaxError and NameError) account for most occurrences.*

1. **Q2.1**  
   ```python
   if 5 > 3
       print("Yes")
   ```  
   **Which error message is generated?**  
   - A. SyntaxError: invalid syntax (missing colon)  
   - B. NameError: name 'print' is not defined  
   - C. TypeError: '>' not supported between operands  
   - D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

2. **Q2.2**  
   ```python
   print(hello)
   ```  
   **What error message does this produce?**  
   - A. NameError: name 'hello' is not defined  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'str' object is not callable  
   - D. None of the above  
   *(Correct Answer: A)*

3. **Q2.3**  
   ```python
   x = 5
   if x == 5:
       print("x is 5"
   ```  
   **Which error message is raised?**  
   - A. SyntaxError: invalid syntax (missing closing parenthesis)  
   - B. NameError: name 'print' is not defined  
   - C. IndentationError: expected an indented block  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q2.4**  
   ```python
   print("Hello)
   ```  
   **What is the error and its location?**  
   - A. SyntaxError: EOL while scanning string literal (missing closing quote)  
   - B. SyntaxError: invalid syntax  
   - C. NameError: name 'print' is not defined  
   - D. IndexError: string index out of range  
   *(Correct Answer: A)*

5. **Q2.5**  
   ```python
   def foo():
       print("bar")
       
   fooo()
   ```  
   **Which error message is produced?**  
   - A. NameError: name 'fooo' is not defined  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'NoneType' object is not callable  
   - D. ValueError: function not found  
   *(Correct Answer: A)*

---

### Aspect 3  
*Novice errors often stem from gaps in fundamental knowledge, whereas experts tend to misread or overlook details.*

1. **Q3.1**  
   ```python
   x = "5"
   y = 3
   print(x - y)
   ```  
   **Which error is raised?**  
   - A. TypeError: unsupported operand type(s) for -: 'str' and 'int'  
   - B. SyntaxError: invalid syntax  
   - C. ValueError: cannot subtract string from int  
   - D. IndexError: invalid index operation  
   *(Correct Answer: A)*

2. **Q3.2**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(10, 0))
   ```  
   **What error message is produced?**  
   - A. ZeroDivisionError: division by zero  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. NameError: divide is not defined  
   *(Correct Answer: A)*

3. **Q3.3**  
   ```python
   numbers = [1, 2, 3]
   print(numbers[3])
   ```  
   **Which error occurs?**  
   - A. IndexError: list index out of range  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: list indices must be integers  
   - D. NameError: numbers is not defined  
   *(Correct Answer: A)*

4. **Q3.4**  
   ```python
   for i in range(3):
       print("Number: " + i)
   ```  
   **Identify the error and specify its location.**  
   - A. The error occurs at the print statement because it attempts to concatenate a string and an integer.  
   - B. The error is in the for-loop syntax.  
   - C. The error is due to an undefined variable.  
   - D. The error is caused by a missing colon.  
   *(Correct Answer: A)*

5. **Q3.5**  
   ```python
   def func():
       return

   print(func(1))
   ```  
   **What error message is produced?**  
   - A. TypeError: func() takes 0 positional arguments but 1 was given  
   - B. SyntaxError: invalid syntax  
   - C. ValueError: too many values  
   - D. NameError: func is not defined  
   *(Correct Answer: A)*

---

### Aspect 4  
*Top errors (such as using an undeclared variable) occur very frequently and are often better spotted by human analysis than by compiler messages.*

1. **Q4.1**  
   ```python
   a = 10
   b = 20
   print(c)
   ```  
   **Which error message is raised?**  
   - A. NameError: name 'c' is not defined  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. IndexError: list index out of range  
   *(Correct Answer: A)*

2. **Q4.2**  
   ```python
   for item in [1, 2, 3]:
       print(itm)
   ```  
   **What error occurs?**  
   - A. NameError: name 'itm' is not defined  
   - B. SyntaxError: invalid syntax  
   - C. None of the above  
   - D. ValueError: undefined variable  
   *(Correct Answer: A)*

3. **Q4.3**  
   ```python
   def square(n):
       return n * n

   result = sqare(4)
   ```  
   **Which error message is produced?**  
   - A. NameError: name 'sqare' is not defined  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. NameError: name 'square' is not defined  
   *(Correct Answer: A)*

4. **Q4.4**  
   ```python
   if x > 10:
       print("x is large")
   ```  
   **Assuming `x` is undefined, where is the error?**  
   - A. In the if condition (using an undefined variable ‘x’).  
   - B. In the print statement.  
   - C. In both the condition and print statement.  
   - D. In the function call.  
   *(Correct Answer: A)*

5. **Q4.5**  
   ```python
   import math
   print(sin(0))
   ```  
   **Explain why this error occurs.**  
   - A. NameError: name 'sin' is not defined because it wasn’t imported from math.  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: math.sin() missing argument  
   - D. IndexError: undefined function  
   *(Correct Answer: A)*

---

### Aspect 5  
*Misconceptions are the most frequent reason for logic errors—mistakes in how methods or attributes are used.*

1. **Q5.1**  
   ```python
   numbers = [3, 1, 2]
   print(numbers.sorted())
   ```  
   **Why does this code raise an error?**  
   - A. Because lists do not have a method named `sorted` (use the built-in function `sorted()` or the list’s `.sort()` method).  
   - B. Because the list is unsorted.  
   - C. Due to a syntax error.  
   - D. Because of a missing colon.  
   *(Correct Answer: A)*

2. **Q5.2**  
   ```python
   class MyClass:
       def __init__(self, value):
           self.value = value

   obj = MyClass(10)
   print(obj.Value)
   ```  
   **What is wrong in this snippet?**  
   - A. The attribute is referenced with the wrong case—it should be `obj.value`.  
   - B. The class is defined incorrectly.  
   - C. There is no error.  
   - D. All of the above  
   *(Correct Answer: A)*

3. **Q5.3**  
   ```python
   data = {"a": 1, "b": 2}
   print(data.a)
   ```  
   **Which error message is raised?**  
   - A. AttributeError: 'dict' object has no attribute 'a'  
   - B. SyntaxError: invalid syntax  
   - C. KeyError: 'a'  
   - D. TypeError: 'dict' object is not callable  
   *(Correct Answer: A)*

4. **Q5.4**  
   ```python
   s = "hello"
   print(s.uppercase())
   ```  
   **Identify the error.**  
   - A. AttributeError: 'str' object has no attribute 'uppercase' (the correct method is `upper()`).  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. NameError: 's' is not defined  
   *(Correct Answer: A)*

5. **Q5.5**  
   ```python
   import math
   print(math.power(2, 3))
   ```  
   **Which error is produced?**  
   - A. AttributeError: module 'math' has no attribute 'power'  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: math.power() takes exactly two arguments  
   - D. IndexError: invalid attribute  
   *(Correct Answer: A)*

---

### Aspect 6  
*Good debuggers know exactly what error messages mean when bugs occur.*

1. **Q6.1**  
   ```python
   def process(items):
       total = 0
       for item in items:
           total += item
       return total

   print(process([1, 2, '3']))
   ```  
   **Which error message is raised?**  
   - A. TypeError: unsupported operand type(s) for +=: 'int' and 'str'  
   - B. NameError: name 'items' is not defined  
   - C. SyntaxError: invalid syntax  
   - D. ValueError: cannot add int and str  
   *(Correct Answer: A)*

2. **Q6.2**  
   ```python
   def get_first_element(lst):
       return lst[0]

   print(get_first_element([]))
   ```  
   **What error message is produced?**  
   - A. IndexError: list index out of range  
   - B. TypeError: 'list' object is not callable  
   - C. NameError: name 'lst' is not defined  
   - D. KeyError: list is empty  
   *(Correct Answer: A)*

3. **Q6.3**  
   ```python
   def concatenate(a, b):
       return a + b

   print(concatenate("Hello", 5))
   ```  
   **Which error message occurs?**  
   - A. TypeError: can only concatenate str (not "int") to str  
   - B. SyntaxError: invalid syntax  
   - C. NameError: concatenate is not defined  
   - D. ValueError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q6.4**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(10, 0))
   ```  
   **What error message is raised?**  
   - A. ZeroDivisionError: division by zero  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. NameError: divide is not defined  
   *(Correct Answer: A)*

5. **Q6.5**  
   ```python
   def access_list(lst):
       return lst[5]

   print(access_list([1, 2, 3]))
   ```  
   **Explain why this error occurs.**  
   - A. Because index 5 is out of range for a list with only 3 elements.  
   - B. Because the list is empty.  
   - C. Because list indexing is not allowed here.  
   - D. Because of a syntax error.  
   *(Correct Answer: A)*

---

### Aspect 7  
*Early tutorials reduce syntax/runtime errors for students, yet logical mistakes remain challenging.*

1. **Q7.1**  
   ```python
   def compute_average(numbers):
       total = sum(numbers)
       avg = total / len(numbers)
       return avg

   print(compute_average([]))
   ```  
   **Which error message is produced?**  
   - A. ZeroDivisionError: division by zero  
   - B. IndexError: list index out of range  
   - C. SyntaxError: invalid syntax  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

2. **Q7.2**  
   ```python
   def find_max(numbers):
       max_val = 0
       for num in numbers:
           if num > max_val:
               max_val = num
       return max_val

   result = find_max([-10, -5, -3])
   ```  
   **What is the logical flaw in this code?**  
   - A. It incorrectly returns 0 instead of the maximum value due to improper initialization of `max_val`.  
   - B. The for-loop is structured incorrectly.  
   - C. The function never returns a value.  
   - D. It raises an exception due to negative numbers.  
   *(Correct Answer: A)*

3. **Q7.3**  
   **Which of the following is true about logic errors in Python?**  
   - A. They produce no compiler or runtime error messages—only incorrect output.  
   - B. They always trigger a SyntaxError.  
   - C. They always result in a NameError.  
   - D. They always cause a runtime exception.  
   *(Correct Answer: A)*

4. **Q7.4**  
   ```python
   def compute_total(values):
       total = 0
       for v in values:
           total = total + v
       return total

   # Intended to add 1 to each value before summing, but it doesn’t.
   print(compute_total([1, 2, 3]))
   ```  
   **Explain the issue in this code.**  
   - A. The function fails to modify each value as intended; it only sums the values directly.  
   - B. There is a syntax error in the for loop.  
   - C. The return statement is missing.  
   - D. The list contains a non-numeric element.  
   *(Correct Answer: A)*

5. **Q7.5**  
   ```python
   def calculate_average(nums):
       total = sum(nums)
       return total / len(nums)

   print(calculate_average([]))
   ```  
   **Which error message is produced?**  
   - A. ZeroDivisionError: division by zero  
   - B. IndexError: list index out of range  
   - C. SyntaxError: invalid syntax  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

---

### Aspect 8  
*Students often make syntax errors (e.g. using the wrong comparison operator or omitting required punctuation).*

1. **Q8.1**  
   ```python
   x = 10
   if x = 10:
       print("x is 10")
   ```  
   **Which error message is produced?**  
   - A. SyntaxError: invalid syntax (assignment operator used instead of '==')  
   - B. NameError: x is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

2. **Q8.2**  
   ```python
   print "Hello, world!"
   ```  
   **In Python 3, what error does this produce?**  
   - A. SyntaxError: Missing parentheses in call to 'print'  
   - B. NameError: print is not defined  
   - C. TypeError: 'str' object is not callable  
   - D. None of the above  
   *(Correct Answer: A)*

3. **Q8.3**  
   ```python
   if x > 5 and:
       print("x is greater than 5")
   ```  
   **What error message is raised?**  
   - A. SyntaxError: invalid syntax (unexpected use of 'and')  
   - B. NameError: x is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. IndexError: operator misuse  
   *(Correct Answer: A)*

4. **Q8.4**  
   ```python
   def greet(name):
       print("Hello, " + name
       
   greet("Alice")
   ```  
   **Identify the error and its location.**  
   - A. SyntaxError: unexpected EOF while parsing (missing closing parenthesis in the function).  
   - B. NameError: name 'name' is not defined.  
   - C. TypeError: unsupported operand type(s) for +.  
   - D. IndentationError: unexpected indent.  
   *(Correct Answer: A)*

5. **Q8.5**  
   ```python
   result = (5 + 3) * 2)
   ```  
   **What error message does this code generate?**  
   - A. SyntaxError: unmatched ')'  
   - B. NameError: result is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. ValueError: invalid literal  
   *(Correct Answer: A)*

---

### Aspect 9  
*Many errors are prevalent across both Python and Java, indicating shared challenges for novices.*

1. **Q9.1**  
   ```python
   a = 5
   if a == 5
       print("a is 5")
   ```  
   **Which error message is produced?**  
   - A. SyntaxError: invalid syntax (missing colon)  
   - B. NameError: a is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

2. **Q9.2**  
   ```python
   my_list = [1, 2, 3]
   print(my_list[3])
   ```  
   **What error occurs?**  
   - A. IndexError: list index out of range  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'list' object is not callable  
   - D. None of the above  
   *(Correct Answer: A)*

3. **Q9.3**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract(10))
   ```  
   **Which error is raised?**  
   - A. TypeError: subtract() missing 1 required positional argument: 'b'  
   - B. NameError: subtract is not defined  
   - C. SyntaxError: invalid syntax  
   - D. ValueError: too few values  
   *(Correct Answer: A)*

4. **Q9.4**  
   ```python
   for i in range(5)
       print(i)
   ```  
   **What error message will this produce?**  
   - A. SyntaxError: invalid syntax (missing colon after the for statement)  
   - B. NameError: i is not defined  
   - C. TypeError: 'int' object is not iterable  
   - D. IndexError: unexpected indent  
   *(Correct Answer: A)*

5. **Q9.5**  
   ```python
   x = "hello"
   print(x[10])
   ```  
   **Which error message is generated?**  
   - A. IndexError: string index out of range  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'str' object is not subscriptable  
   - D. None of the above  
   *(Correct Answer: A)*

---

### Aspect 10  
*Certain recurring errors (linked to bad habits) can be automatically flagged.*

1. **Q10.1**  
   ```python
   class MyClass:
       def __init__(self, value):
           self.value = value
       def display():
           print(self.value)

   obj = MyClass(10)
   obj.display()
   ```  
   **Which error occurs and where?**  
   - A. TypeError: display() missing 1 required positional argument: 'self' (the method lacks the proper parameter).  
   - B. SyntaxError: invalid syntax  
   - C. AttributeError: 'MyClass' object has no attribute 'display'  
   - D. IndexError: function call error  
   *(Correct Answer: A)*

2. **Q10.2**  
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
   **Identify the mistake in the `area` method.**  
   - A. The attributes `width` and `height` are not referenced with `self.` inside the method.  
   - B. The method should accept an extra parameter.  
   - C. The constructor is defined incorrectly.  
   - D. There is no error.  
   *(Correct Answer: A)*

3. **Q10.3**  
   ```python
   def add(a, b):
       return a + b

   result = add(1, 2, 3)
   ```  
   **What is wrong with this function call?**  
   - A. Too many arguments are passed to the function `add`.  
   - B. The function definition is missing a colon.  
   - C. The return statement is incorrect.  
   - D. The function name is misspelled.  
   *(Correct Answer: A)*

4. **Q10.4**  
   ```python
   x = 10
   if x == 10:
   print("x is ten")
   ```  
   **Where is the error located?**  
   - A. The print statement should be indented within the if block.  
   - B. The if statement is missing a colon.  
   - C. The variable `x` is undefined.  
   - D. The function call is incorrect.  
   *(Correct Answer: A)*

5. **Q10.5**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract("10", "5"))
   ```  
   **Explain why this error occurs.**  
   - A. Subtraction is not defined between string operands.  
   - B. The function `subtract()` is called with arguments of the wrong type.  
   - C. Both A and B.  
   - D. The function is missing a return statement.  
   *(Correct Answer: A)*

---

### Aspect 11  
*Experts resolve basic errors quickly and accurately.*

1. **Q11.1**  
   ```python
   print("Hello, world!"
   ```  
   **What error message is produced?**  
   - A. SyntaxError: unexpected EOF while parsing  
   - B. NameError: name 'print' is not defined  
   - C. IndentationError: unexpected indent  
   - D. TypeError: 'str' object is not callable  
   *(Correct Answer: A)*

2. **Q11.2**  
   ```python
   x = [1, 2, 3]
   print(x[3])
   ```  
   **Which error message occurs?**  
   - A. IndexError: list index out of range  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'list' object is not callable  
   - D. NameError: x is not defined  
   *(Correct Answer: A)*

3. **Q11.3**  
   ```python
   def multiply(a, b):
       return a * b

   print(multiply(2))
   ```  
   **What error is raised?**  
   - A. TypeError: multiply() missing 1 required positional argument: 'b'  
   - B. SyntaxError: invalid syntax  
   - C. NameError: multiply is not defined  
   - D. ValueError: too many values  
   *(Correct Answer: A)*

4. **Q11.4**  
   ```python
   x = "100a"
   y = int(x)
   ```  
   **Explain the error and its meaning.**  
   - A. ValueError: invalid literal for int() with base 10: '100a' (the string cannot be converted to an integer).  
   - B. TypeError: cannot convert string to int  
   - C. SyntaxError: invalid syntax  
   - D. NameError: x is not defined  
   *(Correct Answer: A)*

5. **Q11.5**  
   ```python
   def get_value(d, key):
       return d[key]

   d = {"a": 1, "b": 2}
   print(get_value(d, "c"))
   ```  
   **Explain why this error occurs.**  
   - A. KeyError: 'c' because the key does not exist in the dictionary.  
   - B. SyntaxError: invalid syntax  
   - C. NameError: d is not defined  
   - D. TypeError: 'dict' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 12  
*Students who make one punctuation error often make related mistakes (e.g., mismatched brackets).*

1. **Q12.1**  
   ```python
   print("Hello, world!"
   ```  
   **What error message is raised?**  
   - A. SyntaxError: unexpected EOF while parsing  
   - B. NameError: print is not defined  
   - C. TypeError: 'str' object is not callable  
   - D. IndexError: missing parenthesis  
   *(Correct Answer: A)*

2. **Q12.2**  
   ```python
   numbers = [1, 2, 3
   print(numbers)
   ```  
   **Which error occurs?**  
   - A. SyntaxError: invalid syntax (missing closing bracket)  
   - B. NameError: numbers is not defined  
   - C. IndexError: list index out of range  
   - D. ValueError: list is incomplete  
   *(Correct Answer: A)*

3. **Q12.3**  
   ```python
   def add(a, b):
       return (a + b

   print(add(5, 3))
   ```  
   **What error is produced?**  
   - A. SyntaxError: unexpected EOF while parsing (due to a missing closing parenthesis)  
   - B. TypeError: unsupported operand type(s)  
   - C. NameError: add is not defined  
   - D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

4. **Q12.4**  
   ```python
   if (5 > 3:
       print("Correct")
   ```  
   **Which error message is raised?**  
   - A. SyntaxError: invalid syntax (missing closing parenthesis in the if condition)  
   - B. NameError: print is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. IndexError: missing condition  
   *(Correct Answer: A)*

5. **Q12.5**  
   ```python
   data = {"key": "value"
   print(data["key"])
   ```  
   **What error message occurs?**  
   - A. SyntaxError: unexpected EOF while parsing (missing closing brace for the dictionary)  
   - B. KeyError: 'key'  
   - C. NameError: data is not defined  
   - D. TypeError: 'dict' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 13  
*Some errors (like identifier resolution issues) consume disproportionate time for all skill levels.*

1. **Q13.1**  
   ```python
   x = 5

   def foo():
       print(x)
       x = 10

   foo()
   ```  
   **Which error message is produced and why?**  
   - A. UnboundLocalError: local variable 'x' referenced before assignment (because x is assigned inside the function without declaring it global).  
   - B. SyntaxError: invalid syntax  
   - C. NameError: x is not defined  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

2. **Q13.2**  
   ```python
   from math import sin
   print(cos(0))
   ```  
   **Explain the error in this snippet.**  
   - A. NameError: name 'cos' is not defined because only `sin` was imported.  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: 'module' object is not callable  
   - D. AttributeError: module 'math' has no attribute 'cos'  
   *(Correct Answer: A)*

3. **Q13.3**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(5, '2'))
   ```  
   **Which error message is produced?**  
   - A. TypeError: unsupported operand type(s) for /: 'int' and 'str'  
   - B. SyntaxError: invalid syntax  
   - C. NameError: divide is not defined  
   - D. ValueError: invalid literal for int() with base 10  
   *(Correct Answer: A)*

4. **Q13.4**  
   ```python
   class Sample:
       def __init__(self, value):
           self.value = value

       def get_value(self):
           return value

   obj = Sample(10)
   print(obj.get_value())
   ```  
   **Where is the error and what is the mistake?**  
   - A. NameError: name 'value' is not defined in `get_value()` (it should return `self.value`).  
   - B. SyntaxError: invalid syntax  
   - C. TypeError: unsupported operand type(s)  
   - D. AttributeError: 'Sample' object has no attribute 'get_value'  
   *(Correct Answer: A)*

5. **Q13.5**  
   ```python
   x = 10
   def modify():
       print(x)
       x = x + 1

   modify()
   ```  
   **What error is produced and why?**  
   - A. UnboundLocalError: local variable 'x' referenced before assignment  
   - B. SyntaxError: invalid syntax  
   - C. NameError: x is not defined  
   - D. TypeError: 'int' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 14  
*Experts use systematic debugging techniques; novices benefit significantly from reference guides.*

1. **Q14.1**  
   ```python
   def compute(value):
       if value > 10
           return value * 2
       else:
           return value + 2

   print(compute(5))
   ```  
   **What error message is generated?**  
   - A. SyntaxError: invalid syntax (missing colon after the if statement)  
   - B. NameError: value is not defined  
   - C. TypeError: unsupported operand type(s)  
   - D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

2. **Q14.2**  
   ```python
   def process_data(data):
       result = []
       for item in data
           result.append(item * 2)
       return result

   print(process_data([1,2,3]))
   ```  
   **Which error message occurs?**  
   - A. SyntaxError: invalid syntax (missing colon after the for loop)  
   - B. NameError: data is not defined  
   - C. TypeError: 'list' object is not callable  
   - D. ValueError: invalid literal  
   *(Correct Answer: A)*

3. **Q14.3**  
   ```python
   def foo():
       print("Starting function")
       x = 5
       if x > 3:
           print("x is greater than 3")
         print("This line is misindented")
   foo()
   ```  
   **Identify the error and its location.**  
   - A. IndentationError: unindent does not match any outer indentation level (on the misindented print statement).  
   - B. SyntaxError: invalid syntax  
   - C. NameError: x is not defined  
   - D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q14.4**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract(10))
   ```  
   **Which error message occurs?**  
   - A. TypeError: subtract() missing 1 required positional argument: 'b'  
   - B. NameError: subtract is not defined  
   - C. SyntaxError: invalid syntax  
   - D. ValueError: too few arguments  
   *(Correct Answer: A)*

5. **Q14.5**  
   ```python
   def get_item(lst, index):
       return lst[index]

   my_list = [1, 2, 3]
   print(get_item(my_list, 5))
   ```  
   **Explain why the error occurs.**  
   - A. IndexError: list index out of range because index 5 does not exist in `my_list`.  
   - B. SyntaxError: invalid syntax  
   - C. NameError: lst is not defined  
   - D. TypeError: 'list' object is not callable  
   *(Correct Answer: A)*
