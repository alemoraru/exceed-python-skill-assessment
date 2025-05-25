# Programming Skill Level MCQ Survey - Version 2

This survey is designed to assess your understanding and ability to identify, understand, and resolve common programming errors across general and Python-specific contexts. The questions are divided into several sections (i.e. aspects), each focusing on a different aspect of error handling in programming:

### Aspect 1  
*Experienced programmers are significantly better at correctly finding and fixing bugs, though not necessarily faster.*  
These questions are designed to see if the respondent carefully reads and identifies the real error in a snippet.

1. **Q1.1**  
   ```python
   def add_numbers(a, b):
       return a + b

   print(add_numbers(5, '3'))
   ```  
   **Which error message is produced?**  
   A. TypeError: unsupported operand type(s) for +: 'int' and 'str'  
   B. SyntaxError: invalid syntax  
   C. ValueError: could not convert string to int  
   D. NameError: name 'add_numbers' is not defined  
   *(Correct Answer: A)*

2. **Q1.2**  
   ```python
   def foo():
   print("Missing indentation")
   ```  
   **Which error message is generated?**  
   A. IndentationError: expected an indented block  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. NameError: name 'foo' is not defined  
   *(Correct Answer: A)*

3. **Q1.3**  
   ```python
   if True:
       print("Hello")
     print("World")
   ```  
   **What error message will this code produce?**  
   A. IndentationError: unexpected indent  
   B. IndentationError: unindent does not match any outer indentation level  
   C. SyntaxError: invalid syntax  
   D. No error; it runs fine  
   *(Correct Answer: B)*

4. **Q1.4**  
   ```python
   def multiply(a, b):
       return a * b

   print(multiply(3))
   ```  
   **What error message is raised?**  
   A. TypeError: multiply() missing 1 required positional argument: 'b'  
   B. ValueError: not enough values to unpack  
   C. SyntaxError: invalid syntax  
   D. IndexError: list index out of range  
   *(Correct Answer: A)*

5. **Q1.5**  
   ```python
   for i in range(5):
       print(i)
   print(j)
   ```  
   **What error message is generated?**  
   A. NameError: name 'j' is not defined  
   B. UnboundLocalError: local variable 'j' referenced before assignment  
   C. SyntaxError: invalid syntax  
   D. IndexError: list index out of range  
   *(Correct Answer: A)*

---

### Aspect 2  
*“A few error types (e.g. SyntaxError: invalid syntax and NameError: name … is not defined) account for most occurrences.”*  

1. **Q2.1**  
   ```python
   if 5 > 3
       print("Yes")
   ```  
   **Which error message is generated?**  
   A. SyntaxError: invalid syntax  
   B. NameError: name 'print' is not defined  
   C. TypeError: '>' not supported  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

2. **Q2.2**  
   ```python
   print(hello)
   ```  
   **What error message does this produce?**  
   A. NameError: name 'hello' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'str' object is not callable  
   D. ValueError: invalid literal  
   *(Correct Answer: A)*

3. **Q2.3**  
   ```python
   x = 5
   if x == 5:
       print("x is 5"
   ```  
   **What error message is raised?**  
   A. SyntaxError: invalid syntax  
   B. NameError: name 'print' is not defined  
   C. IndentationError: expected an indented block  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q2.4**  
   ```python
   print("Hello)
   ```  
   **Which error message best describes the issue?**  
   A. SyntaxError: EOL while scanning string literal  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'print' is not defined  
   D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

5. **Q2.5**  
   ```python
   def foo():
       print("bar")
       
   fooo()
   ```  
   **What error message is produced?**  
   A. NameError: name 'fooo' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'NoneType' object is not callable  
   D. AttributeError: module has no attribute 'fooo'  
   *(Correct Answer: A)*

---

### Aspect 3  
*“Novice errors often stem from gaps in fundamental knowledge, while experts tend to misread or overlook details.”*  

1. **Q3.1**  
   ```python
   x = "5"
   y = 3
   print(x - y)
   ```  
   **Which error is raised?**  
   A. TypeError: unsupported operand type(s) for -: 'str' and 'int'  
   B. SyntaxError: invalid syntax  
   C. ValueError: cannot subtract str from int  
   D. NameError: name 'x' is not defined  
   *(Correct Answer: A)*

2. **Q3.2**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(10, 0))
   ```  
   **What error message is produced?**  
   A. ZeroDivisionError: division by zero  
   B. SyntaxError: invalid syntax  
   C. ValueError: division by zero  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

3. **Q3.3**  
   ```python
   numbers = [1, 2, 3]
   print(numbers[3])
   ```  
   **What error occurs?**  
   A. IndexError: list index out of range  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'list' object is not callable  
   D. NameError: name 'numbers' is not defined  
   *(Correct Answer: A)*

4. **Q3.4**  
   ```python
   for i in range(3):
       print("Number: " + i)
   ```  
   **What error is raised?**  
   A. TypeError: can only concatenate str (not "int") to str  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'i' is not defined  
   D. ValueError: invalid literal for int() with base 10  
   *(Correct Answer: A)*

5. **Q3.5**  
   ```python
   def func():
       return

   print(func(1))
   ```  
   **What error message is produced?**  
   A. TypeError: func() takes 0 positional arguments but 1 was given  
   B. SyntaxError: invalid syntax  
   C. ValueError: too many arguments  
   D. NameError: name 'func' is not defined  
   *(Correct Answer: A)*

---

### Aspect 4  
*“Top errors (e.g. undeclared variables) occur very frequently and are often better spotted by human analysis than by compiler messages.”*  

1. **Q4.1**  
   ```python
   a = 10
   b = 20
   print(c)
   ```  
   **Which error message is raised?**  
   A. NameError: name 'c' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. IndexError: list index out of range  
   *(Correct Answer: A)*

2. **Q4.2**  
   ```python
   for item in [1, 2, 3]:
       print(itm)
   ```  
   **What error occurs?**  
   A. NameError: name 'itm' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. AttributeError: 'int' object has no attribute 'itm'  
   *(Correct Answer: A)*

3. **Q4.3**  
   ```python
   def square(n):
       return n * n

   result = sqare(4)
   ```  
   **Which error message is produced?**  
   A. NameError: name 'sqare' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. AttributeError: 'int' object has no attribute 'sqare'  
   *(Correct Answer: A)*

4. **Q4.4**  
   ```python
   if x > 10:
       print("x is large")
   ```  
   **Assuming `x` is undefined, what error occurs?**  
   A. NameError: name 'x' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: '>' not supported between instances  
   D. ValueError: x must be a number  
   *(Correct Answer: A)*

5. **Q4.5**  
   ```python
   import math
   print(sin(0))
   ```  
   **What error message is raised?**  
   A. NameError: name 'sin' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: sin() takes exactly one argument (0 given)  
   D. AttributeError: module 'math' has no attribute 'sin'  
   *(Correct Answer: A)*

---

### Aspect 5  
*“Misconceptions are the most frequent reason for logic errors – mistakes in how methods or attributes are used.”*  

1. **Q5.1**  
   ```python
   numbers = [3, 1, 2]
   print(numbers.sorted())
   ```  
   **Which error message is produced?**  
   A. AttributeError: 'list' object has no attribute 'sorted'  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'list' object is not callable  
   D. ValueError: invalid literal for int()  
   *(Correct Answer: A)*

2. **Q5.2**  
   ```python
   class MyClass:
       def __init__(self, value):
           self.value = value

   obj = MyClass(10)
   print(obj.Value)
   ```  
   **What error occurs?**  
   A. AttributeError: 'MyClass' object has no attribute 'Value'  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'Value' is not defined  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

3. **Q5.3**  
   ```python
   data = {"a": 1, "b": 2}
   print(data.a)
   ```  
   **Which error message is raised?**  
   A. AttributeError: 'dict' object has no attribute 'a'  
   B. SyntaxError: invalid syntax  
   C. KeyError: 'a'  
   D. NameError: name 'data' is not defined  
   *(Correct Answer: A)*

4. **Q5.4**  
   ```python
   s = "hello"
   print(s.uppercase())
   ```  
   **What error message is generated?**  
   A. AttributeError: 'str' object has no attribute 'uppercase'  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'uppercase' is not defined  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

5. **Q5.5**  
   ```python
   import math
   print(math.power(2, 3))
   ```  
   **Which error occurs?**  
   A. AttributeError: module 'math' has no attribute 'power'  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. ValueError: math domain error  
   *(Correct Answer: A)*

---

### Aspect 6  
*“Good debuggers (and good programmers) know exactly what error messages mean when bugs occur.”*  

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
   A. TypeError: unsupported operand type(s) for +=: 'int' and 'str'  
   B. NameError: name 'items' is not defined  
   C. SyntaxError: invalid syntax  
   D. AttributeError: 'list' object has no attribute 'append'  
   *(Correct Answer: A)*

2. **Q6.2**  
   ```python
   def get_first_element(lst):
       return lst[0]

   print(get_first_element([]))
   ```  
   **What error message is produced?**  
   A. IndexError: list index out of range  
   B. TypeError: 'list' object is not callable  
   C. NameError: name 'lst' is not defined  
   D. ValueError: empty sequence  
   *(Correct Answer: A)*

3. **Q6.3**  
   ```python
   def concatenate(a, b):
       return a + b

   print(concatenate("Hello", 5))
   ```  
   **Which error message occurs?**  
   A. TypeError: can only concatenate str (not "int") to str  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'concatenate' is not defined  
   D. ValueError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q6.4**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(10, 0))
   ```  
   **What error message is raised?**  
   A. ZeroDivisionError: division by zero  
   B. TypeError: unsupported operand type(s)  
   C. SyntaxError: invalid syntax  
   D. ValueError: division by zero  
   *(Correct Answer: A)*

5. **Q6.5**  
   ```python
   def access_list(lst):
       return lst[5]

   print(access_list([1, 2, 3]))
   ```  
   **Which error occurs?**  
   A. IndexError: list index out of range  
   B. NameError: name 'lst' is not defined  
   C. SyntaxError: invalid syntax  
   D. TypeError: 'list' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 7  
*“Early tutorials reduce syntax/runtime errors, yet logical mistakes (which sometimes do produce runtime errors) remain challenging.”*  

1. **Q7.1**  
   ```python
   def compute_average(numbers):
       total = sum(numbers)
       avg = total / len(numbers)
       return avg

   print(compute_average([]))
   ```  
   **What error message is produced?**  
   A. ZeroDivisionError: division by zero  
   B. IndexError: list index out of range  
   C. SyntaxError: invalid syntax  
   D. NameError: name 'numbers' is not defined  
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
   **What is the issue with this code?**  
   A. It incorrectly returns 0 instead of the maximum value due to improper initialization.  
   B. It raises ZeroDivisionError.  
   C. It causes an IndexError.  
   D. It triggers a SyntaxError due to missing colon.  
   *(Correct Answer: A)*

3. **Q7.3**  
   **Which of the following is true about logic errors in Python?**  
   A. They produce no compiler or runtime error messages—only incorrect output.  
   B. They always trigger a SyntaxError.  
   C. They result in a NameError.  
   D. They raise a RuntimeError.  
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
   **What is the issue here?**  
   A. The function does not modify each element as intended (a logic error).  
   B. It raises a TypeError.  
   C. It raises a SyntaxError.  
   D. It raises a NameError.  
   *(Correct Answer: A)*

5. **Q7.5**  
   *(Same as Q7.1)*  
   ```python
   def calculate_average(nums):
       total = sum(nums)
       return total / len(nums)

   print(calculate_average([]))
   ```  
   **Which error message is produced?**  
   A. ZeroDivisionError: division by zero  
   B. IndexError: list index out of range  
   C. TypeError: unsupported operand type(s)  
   D. ValueError: empty sequence  
   *(Correct Answer: A)*

---

### Aspect 8  
*“Students often make syntax errors such as using the wrong comparison operator or omitting required punctuation.”*  

1. **Q8.1**  
   ```python
   x = 10
   if x = 10:
       print("x is 10")
   ```  
   **Which error message is produced?**  
   A. SyntaxError: invalid syntax  
   B. NameError: name 'x' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

2. **Q8.2**  
   ```python
   print "Hello, world!"
   ```  
   **In Python 3, what error message does this produce?**  
   A. SyntaxError: Missing parentheses in call to 'print'  
   B. NameError: name 'print' is not defined  
   C. TypeError: 'str' object is not callable  
   D. ValueError: invalid literal  
   *(Correct Answer: A)*

3. **Q8.3**  
   ```python
   if x > 5 and:
       print("x is greater than 5")
   ```  
   **What error message is raised?**  
   A. SyntaxError: invalid syntax  
   B. NameError: name 'x' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

4. **Q8.4**  
   ```python
   def greet(name):
       print("Hello, " + name

   greet("Alice")
   ```  
   **Which error message is produced?**  
   A. SyntaxError: unexpected EOF while parsing  
   B. NameError: name 'name' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

5. **Q8.5**  
   ```python
   result = (5 + 3) * 2)
   ```  
   **What error message does this code generate?**  
   A. SyntaxError: unmatched ')'  
   B. NameError: name 'result' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. ValueError: invalid literal  
   *(Correct Answer: A)*

---

### Aspect 9  
*“Common errors span multiple languages—issues like missing variables or wrong function calls occur in both Python and Java.”*  

1. **Q9.1**  
   ```python
   a = 5
   if a == 5
       print("a is 5")
   ```  
   **Which error message is produced?**  
   A. SyntaxError: invalid syntax (missing colon)  
   B. NameError: name 'a' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

2. **Q9.2**  
   ```python
   my_list = [1, 2, 3]
   print(my_list[3])
   ```  
   **What error occurs?**  
   A. IndexError: list index out of range  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'my_list' is not defined  
   D. TypeError: 'list' object is not callable  
   *(Correct Answer: A)*

3. **Q9.3**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract(10))
   ```  
   **Which error is raised?**  
   A. TypeError: subtract() missing 1 required positional argument: 'b'  
   B. NameError: name 'subtract' is not defined  
   C. SyntaxError: invalid syntax  
   D. ValueError: not enough values  
   *(Correct Answer: A)*

4. **Q9.4**  
   ```python
   for i in range(5)
       print(i)
   ```  
   **What error message will this produce?**  
   A. SyntaxError: invalid syntax (missing colon)  
   B. NameError: name 'i' is not defined  
   C. TypeError: 'int' object is not iterable  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

5. **Q9.5**  
   ```python
   x = "hello"
   print(x[10])
   ```  
   **Which error message is generated?**  
   A. IndexError: string index out of range  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'x' is not defined  
   D. TypeError: 'str' object is not subscriptable  
   *(Correct Answer: A)*

---

### Aspect 10  
*“Certain recurring errors (often linked to bad habits) can be automatically flagged; these questions check if the user recognizes mistakes that less careful programmers often make.”*  

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
   **Which error is produced?**  
   A. TypeError: display() missing 1 required positional argument: 'self'  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'self' is not defined  
   D. AttributeError: 'MyClass' object has no attribute 'display'  
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
   **What error occurs?**  
   A. NameError: name 'width' is not defined  
   B. TypeError: 'int' object is not callable  
   C. SyntaxError: invalid syntax  
   D. AttributeError: 'Rectangle' object has no attribute 'area'  
   *(Correct Answer: A)*

3. **Q10.3**  
   ```python
   def add(a, b):
       return a + b

   result = add(1, 2, 3)
   ```  
   **Which error message is raised?**  
   A. TypeError: add() takes 2 positional arguments but 3 were given  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'add' is not defined  
   D. ValueError: too many values  
   *(Correct Answer: A)*

4. **Q10.4**  
   ```python
   x = 10
   if x == 10:
   print("x is ten")
   ```  
   **What error message is produced?**  
   A. IndentationError: expected an indented block  
   B. NameError: name 'print' is not defined  
   C. SyntaxError: invalid syntax  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

5. **Q10.5**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract("10", "5"))
   ```  
   **Which error is raised?**  
   A. TypeError: unsupported operand type(s) for -: 'str' and 'str'  
   B. SyntaxError: invalid syntax  
   C. ValueError: invalid literal for int() with base 10  
   D. NameError: name 'subtract' is not defined  
   *(Correct Answer: A)*

---

### Aspect 11  
*“Experts tend to resolve basic errors very quickly and accurately. These questions focus on common, straightforward errors.”*  

1. **Q11.1**  
   ```python
   print("Hello, world!"
   ```  
   **What error message is produced?**  
   A. SyntaxError: unexpected EOF while parsing  
   B. NameError: name 'print' is not defined  
   C. TypeError: 'str' object is not callable  
   D. IndentationError: unexpected indent  
   *(Correct Answer: A)*

2. **Q11.2**  
   ```python
   x = [1, 2, 3]
   print(x[3])
   ```  
   **Which error message occurs?**  
   A. IndexError: list index out of range  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'list' object is not callable  
   D. NameError: name 'x' is not defined  
   *(Correct Answer: A)*

3. **Q11.3**  
   ```python
   def multiply(a, b):
       return a * b

   print(multiply(2))
   ```  
   **What error is raised?**  
   A. TypeError: multiply() missing 1 required positional argument: 'b'  
   B. NameError: multiply is not defined  
   C. SyntaxError: invalid syntax  
   D. ValueError: too many values to unpack  
   *(Correct Answer: A)*

4. **Q11.4**  
   ```python
   x = "100a"
   y = int(x)
   ```  
   **Which error message is generated?**  
   A. ValueError: invalid literal for int() with base 10: '100a'  
   B. TypeError: unsupported operand type(s)  
   C. SyntaxError: invalid syntax  
   D. NameError: name 'x' is not defined  
   *(Correct Answer: A)*

5. **Q11.5**  
   ```python
   def get_value(d, key):
       return d[key]

   d = {"a": 1, "b": 2}
   print(get_value(d, "c"))
   ```  
   **What error message is produced?**  
   A. KeyError: 'c'  
   B. NameError: name 'd' is not defined  
   C. SyntaxError: invalid syntax  
   D. TypeError: 'dict' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 12  
*“Students who make one bracket or punctuation error often make related mistakes. These questions focus on missing or mismatched brackets.”*  

1. **Q12.1**  
   ```python
   print("Hello, world!"
   ```  
   **What error message is raised?**  
   A. SyntaxError: unexpected EOF while parsing  
   B. NameError: name 'print' is not defined  
   C. TypeError: 'str' object is not callable  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

2. **Q12.2**  
   ```python
   numbers = [1, 2, 3
   print(numbers)
   ```  
   **Which error message occurs?**  
   A. SyntaxError: invalid syntax (due to missing closing bracket)  
   B. NameError: name 'numbers' is not defined  
   C. TypeError: 'list' object is not callable  
   D. IndexError: list index out of range  
   *(Correct Answer: A)*

3. **Q12.3**  
   ```python
   def add(a, b):
       return (a + b

   print(add(5, 3))
   ```  
   **What error is produced?**  
   A. SyntaxError: unexpected EOF while parsing  
   B. NameError: name 'add' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: expected an indented block  
   *(Correct Answer: A)*

4. **Q12.4**  
   ```python
   if (5 > 3:
       print("Correct")
   ```  
   **Which error message is raised?**  
   A. SyntaxError: invalid syntax  
   B. NameError: name 'print' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndexError: list index out of range  
   *(Correct Answer: A)*

5. **Q12.5**  
   ```python
   data = {"key": "value"
   print(data["key"])
   ```  
   **What error message occurs?**  
   A. SyntaxError: unexpected EOF while parsing  
   B. NameError: name 'data' is not defined  
   C. KeyError: 'key'  
   D. TypeError: 'dict' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 13  
*“Some errors – like identifier resolution issues – consume disproportionate time. These questions target errors that experts resolve quickly.”*  

1. **Q13.1**  
   ```python
   x = 5

   def foo():
       print(x)
       x = 10

   foo()
   ```  
   **Which error message is generated?**  
   A. UnboundLocalError: local variable 'x' referenced before assignment  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'x' is not defined  
   D. TypeError: 'int' object is not callable  
   *(Correct Answer: A)*

2. **Q13.2**  
   ```python
   from math import sin
   print(cos(0))
   ```  
   **What error occurs?**  
   A. NameError: name 'cos' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: 'module' object is not callable  
   D. AttributeError: module 'math' has no attribute 'cos'  
   *(Correct Answer: A)*

3. **Q13.3**  
   ```python
   def divide(a, b):
       return a / b

   print(divide(5, '2'))
   ```  
   **Which error message is produced?**  
   A. TypeError: unsupported operand type(s) for /: 'int' and 'str'  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'divide' is not defined  
   D. ValueError: invalid literal for int() with base 10  
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
   **What error occurs?**  
   A. NameError: name 'value' is not defined  
   B. SyntaxError: invalid syntax  
   C. TypeError: unsupported operand type(s)  
   D. AttributeError: 'Sample' object has no attribute 'get_value'  
   *(Correct Answer: A)*

5. **Q13.5**  
   ```python
   x = 10
   def modify():
       print(x)
       x = x + 1

   modify()
   ```  
   **Which error message is raised?**  
   A. UnboundLocalError: local variable 'x' referenced before assignment  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'x' is not defined  
   D. TypeError: 'int' object is not callable  
   *(Correct Answer: A)*

---

### Aspect 14  
*“Experts employ systematic debugging; these questions involve errors that are typically resolved by consulting reference guides.”*  

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
   A. SyntaxError: invalid syntax (missing colon after if statement)  
   B. NameError: name 'value' is not defined  
   C. TypeError: unsupported operand type(s)  
   D. IndentationError: unexpected indent  
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
   A. SyntaxError: invalid syntax (missing colon after for loop)  
   B. NameError: name 'data' is not defined  
   C. TypeError: 'list' object is not callable  
   D. ValueError: invalid literal for int()  
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
   **What error is produced?**  
   A. IndentationError: unindent does not match any outer indentation level  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'x' is not defined  
   D. TypeError: unsupported operand type(s)  
   *(Correct Answer: A)*

4. **Q14.4**  
   ```python
   def subtract(a, b):
       return a - b

   print(subtract(10))
   ```  
   **Which error message occurs?**  
   A. TypeError: subtract() missing 1 required positional argument: 'b'  
   B. NameError: subtract is not defined  
   C. SyntaxError: invalid syntax  
   D. ValueError: too many values  
   *(Correct Answer: A)*

5. **Q14.5**  
   ```python
   def get_item(lst, index):
       return lst[index]

   my_list = [1, 2, 3]
   print(get_item(my_list, 5))
   ```  
   **What error is raised?**  
   A. IndexError: list index out of range  
   B. SyntaxError: invalid syntax  
   C. NameError: name 'lst' is not defined  
   D. TypeError: 'list' object is not callable  
   *(Correct Answer: A)*
