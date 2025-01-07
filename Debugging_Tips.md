# **Debugging Tips for Python Beginners**

Debugging is a normal and important part of coding! When your code doesn’t work as expected, don’t panic—use these tips to figure out what went wrong and fix it.

---

## **Common Errors and How to Fix Them**

### **1. Syntax Errors**
Python tells you when something is written incorrectly. Look for these:

- **Missing quotes**:
  ```python
  print(Hello)  # ❌ SyntaxError
  print("Hello")  # ✅ Correct
  ```

- **Missing parentheses**:
  ```python
  print "Hello"  # ❌ SyntaxError
  print("Hello")  # ✅ Correct
  ```

- **Extra spaces or missing spaces**:
  ```python
  print ("Hello")  # ❌ SyntaxError (extra space between `print` and `(`)
  print("Hello")  # ✅ Correct

  print("Hello" )  # ❌ SyntaxError (extra space before `)`)
  print("Hello")  # ✅ Correct
  ```

---

### **2. Name Errors**
This happens when Python doesn’t recognize a name you’ve used.

- **Common Causes**:
  - Typos in variable names:
    ```python
    my_name = "Zachary"
    print(myname)  # ❌ NameError (typo in "myname")
    print(my_name)  # ✅ Correct
    ```

  - Using a variable before defining it:
    ```python
    print(age)  # ❌ NameError
    age = 10  # ✅ Define the variable first!
    print(age)  # ✅ Correct
    ```

---

### **3. Type Errors**
This happens when you mix up data types.

- **Common Example**:
  - Trying to combine strings and numbers directly:
    ```python
    age = 10
    print("I am " + age + " years old")  # ❌ TypeError
    print("I am " + str(age) + " years old")  # ✅ Use str() to convert the number to a string.
    ```

---

### **4. Input Errors**
Using the `input()` function can sometimes lead to unexpected errors. Here are some common ones:

- **Forgetting to store the input in a variable**:
  ```python
  input("What is your name?")  # ❌ Input is entered but not saved
  name = input("What is your name?")  # ✅ Correct
  ```

- **Expecting a number but getting a string**:
  ```python
  age = input("How old are you?")  # ❌ This stores the input as a string, not a number
  age = int(input("How old are you?"))  # ✅ Use int() to convert the input to a number
  ```

  - **ValueError when converting input**:
    If a user enters something that isn’t a number:
    ```python
    age = int(input("Enter your age: "))  # ❌ ValueError if the user types "ten"
    ```
    - To prevent this, you can remind the user to enter a number:
      ```python
      age = input("Enter your age as a number: ")
      age = int(age)  # Works if the input is valid
      ```

---



## **Steps for Debugging Your Code**

1. **Read the Error Message**
   - Python’s error messages can help you understand what went wrong and where.

2. **Check Your Code Line by Line**
   - Look at the line mentioned in the error and any lines right before it.

3. **Run Smaller Sections of Code**
   - If you’re using a Jupyter notebook, try running just one cell at a time to isolate the problem.

4. **Ask for Help**
   - Share the error message with your instructor or look for clues in the example file.

---

## **Tips for Avoiding Bugs**

- Always double-check your spelling, quotes, and parentheses.
- Avoid adding unnecessary spaces between commands and their required syntax.
- Use clear and consistent variable names.
- Test your code after every small change.

---

Mistakes are part of the learning process—don’t be afraid of them! Debugging will help you get better at understanding how Python works.

