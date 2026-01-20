# SyntaX (for Python) 🚀

**SyntaX** is a lightweight utility wrapper designed to provide **consistent naming conventions** across the **SyntaX Ecosystem**.

While Python is already simple, **SyntaX** brings a unified structure for developers moving between C++, Java, C#, and Python. It ensures that your favorite helper functions have the same names and behavior across all your projects.

---

## 🌟 Key Features

* **Ecosystem Consistency:** Shared function names like `print_s()`, `input_s()`, and `randint()`.
* **Standardized Utilities:** Simplified system commands like `clear()` and `sleep()`.
* **OS Agnostic:** Built-in support for both Windows (CMD) and Linux/Unix terminals.
* **Wrapper Philosophy:** Zero overhead; it simply wraps Python's native power into the SyntaX standard.
* **Human-Readable Math:** Unified `square_root` and `factorial` functions.

---

## 🛠️ Usage & Examples

To keep this documentation clean, we have provided a dedicated example file. You can find comprehensive usage examples covering:

* **Unified I/O** (print_s and input_s)
* **Math Helpers** (randint, square_root)
* **System Utilities** (clear screen and sleep)

👉 **Check out [samples.py](./samples.py) for ready-to-use code snippets!**

---

## 📂 Installation

1. Download the **bettersyntax.py** file.
2. Place it in your project's root directory.
3. Import the functions at the top of your script using the `from ... import` statement.

---

## 🚀 Advanced Installation (System-wide)

If you want to use **SyntaX** in every Python script:

1. Copy `bettersyntax.py` to your Python's `site-packages` folder.
2. Alternatively, add the file's path to your `PYTHONPATH` environment variable.
3. Now you can import `bettersyntax` from anywhere!

---

## 💻 Technical Details

SyntaX for Python acts as a standardized wrapper. It uses the `os` and `time` modules to provide cross-platform terminal control. By maintaining the flexible output format required by the SyntaX global standard, it ensures seamless transitions for multi-language developers.

---

## Development Comparison

| Feature | Standard Python (Vanilla) | **SyntaX for Python** (`bettersyntax`) |
| :--- | :--- | :--- |
| **Output** | `print(x, y)` | `print_s(x, y)` |
| **User Input** | `s = input("Name: ")` | `s = input_s("Name: ")` |
| **Random Number** | `random.randint(min, max)` | `randint(min, max)` |
| **Sleep/Wait** | `time.sleep(1.0)` | `sleep(1.0)` |
| **Math (Sqrt)** | `math.sqrt(val)` | `square_root(val)` |
| **Clear Screen** | `os.system('cls' or 'clear')` | `clear()` |

---

### 👨‍💻 Programmer
**hypernova-developer**
