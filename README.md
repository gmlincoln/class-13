# 🐍 PYTHON CLASS 1 - BASIC SETUP & FIRST CODE

### 1️⃣ VS Code Installation
💡 Download and install **Visual Studio Code (VS Code)** from [https://code.visualstudio.com](https://code.visualstudio.com)

---

### 2️⃣ VS Code Extensions
Install the following extensions:  
🧩 **Python**  
🐞 **Python Debugger**  
⚡ **Code Runner**  

---


✅ Download and install **Python** from [https://python.org](https://python.org)

---

### 4️⃣ Check Python Version
```python
# 🪟 Windows
python --version

# 🍎 Mac
python3 --version

```
---

### 5️⃣ PyCharm Installation (Optional)

💡 Optional but useful: Install PyCharm from [https://jetbrains.com/pycharm](https://jetbrains.com/pycharm)

---

### 6️⃣ What is Python?

🐍 Python is:
- **A high-level programming language**  
- **Interpreted (runs line by line)**  
- **Known for simplicity and readability**  
- **👨‍💻 Created by Guido van Rossum in 1991**  

---


### 7️⃣ Why Learn Python?

**✅ Simplicity – Easy to learn and understand**  
**✅ Versatility – Used in many fields**  
**✅ Large Community – Tons of tutorials, help & libraries**  

---

### 8️⃣ Real-world Applications

**🌐 Web Development**  
**📊 Data Science & Machine Learning**  
**⚙️ Automation & Web Scraping**  
**🔌 Embedded Systems**  

---


### 9️⃣ Writing & Running Your First Python Program

📄 Create a file called first.py

Example:
```python
print("Hello, I am learning Python!")
```
▶️ Run the Program

Using → click the Run button

Using Terminal:
```python
# 🪟 Windows
python first.py

# 🍎 Mac
python3 first.py
```
---

### 🔟 How Python Code Executes

**🧠 Executes line by line**  
**🐞 Makes debugging simple**  
**💡 Easy to understand code flow**  

---

### 1️⃣1️⃣ Understanding Code Execution & Debugging

**🔍 Debugging helps you find and fix errors**  
**🧩 Helps break down complex logic**  
**🚀 Improves understanding of performance and others’ code**  

---

### 1️⃣2️⃣Python Comments

**💬 Single-line Comment**
```python
    # This is a single-line comment
```

**📝 Multi-line Comment**
```python
    """
    This is a
    multi-line comment
    """
```


## 🌟 BASIC PYTHON CONCEPTS

### 1️⃣ Getting User Input

```python
name = input("Enter your name: ")
age = input("Enter your age: ")
print("Hello,", name)
print("You are", age, "years old")

```

### 2️⃣ Checking Data Types

```python
x = 10
y = "Python"
print(type(x))  # <class 'int'>
print(type(y))  # <class 'str'>

```

### 3️⃣ Converting Input Types

```python

# Single input
age = int(input("Enter your age: "))

# Multiple inputs
a, b = map(int, input("Enter two numbers separated by space: ").split())
print("Sum:", a + b)


```

### 4️⃣ Concatenation

```python

first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print("Full Name:", full_name)

```
### Python Strings
#### Slicing
```python
    greetings = "Hello, World!"
    print(greetings[2:5]) #Output: llo
    #Slice From the Start
    print(greetings[:5]) #Output: Hello
    #Slice To the End
    print(greetings[2:]) #Output: llo, World!
    print(greetings[-5:-2]) #Output: llo, orl
    
```

##### Modify Strings

```python

    name = "lincoln"
    #Upper Case
    print(name.upper()) #Output: LINCOLN

    #Lower Case
    print(name.lower()) #Output: lincoln

    #Capitalize First Letter
    print(name.capitalize()) #Output: Lincoln

    #Remove Whitespace
    demo = " New Age"
    print(demo.strip()) #Output:New Age

    #Replace String
    print(name.replace("L", "GM L")) #Output: GM Lincoln

    #Split String
    print(demo.strip().split(" ")) #Output: [New, Age]

    #Title
    text = "Welcome to my world"
    x = text.title()
    print(x)

    #Escape Characters
    sentence = "We are the so-called \" Vikings \" from the north."
    print(sentence)  #Output: We are the so-called "Vikings" from the north.
```



### 5️⃣ Operators

| Operator | Example   | Result   |
| -------- | --------- | -------- |
| `+`      | `2 + 3`   | `5`      |
| `-`      | `5 - 2`   | `3`      |
| `*`      | `3 * 4`   | `12`     |
| `/`      | `10 / 3`  | `3.3333` |
| `//`     | `10 // 3` | `3`      |
| `**`     | `2 ** 3`  | `8`      |
| `%`      | `10 % 3`  | `1`      |



### 6️⃣ f-Strings (Formatted Strings)

```python

name = "Lincoln"
age = 20
print(f"My name is {name} and I am {age} years old")

```

### 7️⃣ Conditional Statements


```python
num = int(input("Enter a number: "))

if num > 0:
    print("Positive number")
elif num < 0:
    print("Negative number")
else:
    print("Zero")

```




### 🎯 Practice Tasks

1. Ask the user for two numbers and print their sum, difference, product, and division.
2. Ask the user for their first and last name and greet them using concatenation and f-string.
3. Ask the user for a number and check if it is even or odd using conditionals.