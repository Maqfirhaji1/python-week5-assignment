# 🐍 Python Fundamentals: Functions, Control Flow & Smart Logic

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![Assignment](https://img.shields.io/badge/PLP--Python-Week--4-emerald.svg)

A modular Python solution demonstrating clean code practices, function encapsulation, boolean expression returns, and argument handling with default values.

---

## 📂 Repository Structure

| File | Purpose | Key Concepts |
| :--- | :--- | :--- |
| `welcome.py` | Generates standardized user welcome messages | Functions, `f-strings`, Code Deduplication |
| `toolbox.py` | Contains utility mathematical and logical functions | Default Arguments, Boolean Expressions, Return Statements |
| `README.md` | Comprehensive assignment documentation | Markdown Formatting |

---

## ⚙️ Function Descriptions

### 1. `welcome(name)`
* **Module:** `welcome.py`
* **Details:** Refactors repetitive print statements into a single, modular function that accepts a user's name and returns a formatted welcome string.

### 2. `double(number)`
* **Module:** `toolbox.py`
* **Details:** Accepts an integer or float and returns its value multiplied by `2`.

### 3. `is_pass(score)`
* **Module:** `toolbox.py`
* **Details:** Evaluates an input score against a benchmark of `50`. Returns `True` if passing, otherwise `False`, utilizing a direct boolean comparison return.

### 4. `greet(name, greeting="Hello")`
* **Module:** `toolbox.py`
* **Details:** Returns a custom greeting. Demonstrates optional parameters by utilizing `"Hello"` as a fallback default when no second argument is passed.

---

## 💡 Developer Reflection

> **Which function was the most challenging to write, and why?**
>
> Writing `greet()` required paying close attention to argument order and default parameters. Balancing flexibility (allowing custom greetings like `"Habari"`) while ensuring a seamless fallback (`"Hello"`) highlighted how Python handles function signatures efficiently. Furthermore, direct boolean returning in `is_pass()` served as a great practice for eliminating redundant `if/else` statements.

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone [https://github.com/](https://github.com/)<your-username>/plp-python-week4.git

# Navigate to the project directory
cd plp-python-week4

# Run welcome.py
python welcome.py

# Run toolbox.py
python toolbox.py