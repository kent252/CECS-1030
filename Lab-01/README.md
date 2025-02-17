# Lab 1: Getting Familiar with a Python Development Environment and Running Your First Program

Welcome to your first step in learning Python! In this lab, you will set up a Python development environment, write and execute your first Python program, and understand the fundamental structure of a Python script. Mastering these basics is crucial for becoming a proficient programmer.

---

## 📌 Objectives:
By the end of this lab, you will be able to:
- Set up and familiarize yourself with a Python development environment.
- Write and run Python scripts.
- Understand the basic syntax and structure of a Python program.
- Execute simple input and output operations.

---

## 🛠 1. Setting Up Your Python Development Environment

Before writing Python code, you need a suitable development environment. Here are some popular choices:

### 1.1 Installing Python
First, you need to install Python on your system. You can download the latest version from the official website:

[Download Python](https://www.python.org/downloads/)

After installation, verify that Python is installed correctly by opening a terminal or command prompt and running:

```bash
python --version
```

or (on some systems):

```bash
python3 --version
```

If Python is installed, you should see an output similar to:

```bash
Python 3.x.x
```

### 1.2 Choosing a Code Editor or IDE
You can write and execute Python code using various tools. Here are some common options:

| Tool            | Description                                           |
|----------------|-------------------------------------------------------|
| **Python IDLE** | A simple built-in editor that comes with Python.     |
| **Jupyter Notebook** | An interactive web-based environment great for data science and educational purposes. |
| **VS Code** | A powerful, lightweight editor with Python support and many extensions. |
| **PyCharm** | A full-featured IDE designed for Python development. |

For this lab, you can use **Python IDLE**, **VS Code**, or simply run Python scripts from the command line.

---

## 📝 2. Writing and Running Your First Python Program

Now that your environment is set up, let's write a simple Python program.

### 2.1 Understanding Python Syntax
Python uses indentation instead of braces `{}` to define code blocks, making it clean and readable. Let's write our first Python program:

```python
# This is a comment
# Let's print 'Hello, Python!' to the console
print("Hello, Python!")
```

### 2.2 Running the Program
To execute the script:

#### 📌 Option 1: Using Python IDLE
1. Open Python IDLE.
2. Click **File** → **New File**.
3. Type the Python code and save the file as `hello.py`.
4. Click **Run** → **Run Module** or press `F5`.

#### 📌 Option 2: Running from the Command Line
1. Save the file as `hello.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where `hello.py` is located.
4. Run the script using:

   ```bash
   python hello.py
   ```

   or

   ```bash
   python3 hello.py
   ```

If everything is correct, you should see the following output:

```
Hello, Python!
```

---

## 🔄 3. Basic Input and Output Operations

Python provides a simple way to interact with users through the `input()` function.

### 3.1 Taking User Input
You can ask the user for their name using the `input()` function:

```python
# Asking for user input
name = input("Enter your name: ")

# Displaying the output
print("Hello, " + name + "! Welcome to Python programming.")
```

### 3.2 Explanation
- `input("Enter your name: ")` prompts the user to enter their name.
- The entered value is stored in the variable `name`.
- `print("Hello, " + name + "! Welcome to Python programming.")` prints a personalized greeting message.

### 3.3 Running the Program
Follow the same steps as before to run the script. When executed, it will look like this:

```
Enter your name: Alice
Hello, Alice! Welcome to Python programming.
```

---

## 🎯 4. Summary

In this lab, you have:
✅ Set up a Python development environment.  
✅ Written and executed your first Python script.  
✅ Learned how to perform input and output operations.  

These fundamental skills will help you move forward to more advanced Python topics. Keep practicing, and happy coding! 🚀

---

## 📚 Additional Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [Python Tutorial for Beginners](https://www.w3schools.com/python/)
- [Python Programming on Real Python](https://realpython.com/)
