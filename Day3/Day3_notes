## 📁 Day3/Day3\_Notes.md

````markdown
# 📘 Day 3 – Python, Data Structures & Deep Learning 🧠

**Course Code:** FSP/AI/CDACPUNE/BCMP/01  
**Conducted by:** NIELIT Delhi  
**Trainer:** Sachin Motwani  
🌐 [sachinlearns.com](https://sachinlearns.com) | 📧 [sachinlearns.nielit@gmail.com](mailto:sachinlearns.nielit@gmail.com)

---

## 🎯 Topics Covered

- Python Syntax, Types & Operators
- Built-in Functions
- Data Structures (List, Tuple, Set, Dictionary)
- Conditionals & Loops
- Neural Networks & Activation Functions
- Deep Learning vs Machine Learning
- TensorFlow Playground Demo
- OpenCV Image Code in Colab

---

## 🐍 Python Fundamentals

### 🔣 File Extension
- `.py` → Python source code

### 🧠 Programming Terms

| Term           | Description                              |
|----------------|------------------------------------------|
| Case Sensitive | `a` ≠ `A`                                |
| Comments       | After `#`, ignored by Python             |
| Variable       | Stores data in memory                    |
| Syntax         | Grammar rules of Python                  |
| Indentation    | Defines code blocks                      |
| Debugging      | Finding and fixing errors in code        |

---

## 🔢 Data Types in Python

### Primitive
- `int`, `float`, `str`, `bool`

### Non-Primitive (Built-in)
- `List`, `Tuple`, `Set`, `Dictionary`

### User-Defined
- `Stack`, `Queue`, `Graph`, `Linked List`, `HashMap`

---

## 📦 Python Data Structures Comparison

| Feature            | List `[ ]` | Tuple `( )` | Set `{ }` | Dictionary `{key:val}` |
|--------------------|------------|-------------|-----------|--------------------------|
| Ordered?           | ✅         | ✅          | ❌        | ✅                      |
| Indexed?           | ✅         | ✅          | ❌        | ✅ (via keys)           |
| Allows Duplicates? | ✅         | ✅          | ❌        | ✅ (values), ❌ keys     |
| Mutable?           | ✅         | ❌          | ✅        | ✅                      |

### 🧠 Analogies

| Structure   | Analogy                         |
|-------------|---------------------------------|
| List        | Seating arrangement             |
| Tuple       | Roll numbers (fixed order)      |
| Set         | Unique sample paper collection  |
| Dictionary  | Word meaning lookup dictionary  |

🔗 Source: [ScholarHat](https://www.scholarhat.com/tutorial/python/data-structures-in-python)

---

## 🌀 Accessing Data Structures

- **List/Tuple** → via index
- **Set** → convert to list for access
- **Dictionary** → via keys

---

## 🧾 Python Operators

| Type        | Operators                      |
|-------------|-------------------------------|
| Arithmetic  | `+`, `-`, `*`, `/`, `%`, `**` |
| Assignment  | `=`, `+=`, `-=`, `*=`, `/=`   |
| Comparison  | `==`, `!=`, `>`, `<`, `>=`, `<=` |
| Logical     | `and`, `or`, `not`            |

---

## 🔁 Loops

### while Loop

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

🔗 [YoungWonks Blog](https://www.youngwonks.com/blog/While-loops-in-Python)

---

### for Loop

```python
for fruit in ["apple", "banana", "cherry"]:
    print(fruit)
```

### Nested Loops

```python
for i in range(2):
    for j in range(3):
        print(i, j)
```

---

## ❓ Conditionals

```python
x = 10
if x > 5:
    print("Greater")
else:
    print("Smaller")
```

### Nested Example

```python
if x > 0:
    if x > 10:
        print("Big")
    else:
        print("Medium")
else:
    print("Small")
```

---

## 🔧 Python Built-in Functions

| Function      | Description                 |
|---------------|-----------------------------|
| `print()`     | Show output                 |
| `input()`     | Take user input             |
| `int()`       | Convert to integer          |
| `float()`     | Convert to float            |
| `str()`       | Convert to string           |
| `bool()`      | Convert to boolean          |
| `abs()`       | Absolute value              |
| `type()`      | Type checker                |
| `len()`       | Count items                 |
| `range()`     | Generate sequence           |

---

## 🎓 Code Example

```python
user_input = input("Enter a number: ")
number = int(user_input)
print("Absolute Value:", abs(number))
print("Data type of input:", type(user_input))
```

---

## 🧠 Neural Network Basics

> A neuron is a building block of the human and artificial brain.

- Human brain ≈ 86 billion neurons
- Neurons carry electrical signals
- In AI, they simulate computation via inputs and weights

---

## ⚙️ Artificial Neuron (Node)

```
Inputs → Weighted Sum → Activation Function → Output
```

```math
z = Σ(wᵢ * xᵢ) + b  
a = f(z)
```

Where:
- `xᵢ`: Inputs
- `wᵢ`: Weights
- `b`: Bias
- `f(z)`: Activation Function
- `a`: Output

---

## 🧬 Activation Functions

| Name           | Formula                      | Description                        |
|----------------|------------------------------|------------------------------------|
| **Sigmoid**    | 1 / (1 + e^-x)               | (0, 1) Range, S-curve              |
| **Tanh**       | `tanh(x)`                    | (-1, 1) Range, zero-centered       |
| **ReLU**       | `max(0, x)`                  | Fast, sparse, can "die"            |
| **Leaky ReLU** | `max(0.1x, x)`               | Fixes dying ReLU                   |
| **Maxout**     | `max(w₁ᵀx + b₁, w₂ᵀx + b₂)`  | Generalizes ReLU                   |
| **ELU**        | `x` if ≥0, else `α(e^x - 1)` | Smooth transition, faster learning |

---

## 🧠 Deep Learning vs Machine Learning

| Feature                | Machine Learning | Deep Learning            |
|------------------------|------------------|---------------------------|
| Manual Feature Extract | ✅               | ❌ (automatic)             |
| Requires Big Data      | ❌               | ✅                         |
| Speed                  | Slower           | Faster (GPU)              |
| Layers                 | 1–2              | Multiple (deep)           |

---

## 🎮 TensorFlow Playground Demo

🔗 [Visit Playground](https://playground.tensorflow.org/)

- Trained on spiral data
- Visualized learning
- Adjusted layers, neurons, learning rate

---

## 🖼️ OpenCV – Display Image in Google Colab

```python
import cv2
from google.colab.patches import cv2_imshow

image_path = '/content/image.jpg'
img = cv2.imread(image_path)

if img is not None:
    cv2_imshow(img)
else:
    print("Image not found.")
```
* 🗂️ Full GitHub repo with auto-folder structure
* 🧾 Printable PDF versions

I'm ready with those if needed!
