# 📅 Day 1: Core Python Concepts

## 🧠 Concepts Covered

### 🔹 What is Python?

Python is a simple and powerful programming language widely used in:

* Data Science
* Machine Learning & AI
* Automation

---

### 🔹 Variables

Variables are used to store data.

```python
name = "Siva"
age = 22
salary = 10000
```

---

### 🔹 Data Types

Different types of data in Python:

```python
x = 10        # int
y = 10.5      # float
name = "Siva" # string
is_ok = True  # boolean
```

---

### 🔹 Input & Output

```python
name = input("Enter your name: ")
print("Hello", name)
```

---

### 🔹 Conditional Statements

```python
age = 18

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
```

---

### 🔹 Loops

**For Loop:**

```python
for i in range(5):
    print(i)
```

**While Loop:**

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

---

## 💻 Hands-on Practice

### 🔥 Task 1: Print Your Info

```python
name = "Siva"
age = 22

print("My name is", name)
print("My age is", age)
```

---

### 🔥 Task 2: Even or Odd Checker

```python
num = int(input("Enter number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

---

### 🔥 Task 3: Sum of First 10 Numbers

```python
total = 0

for i in range(1, 11):
    total += i

print(total)
```

---

## 🛠️ Mini Project: Student Result Checker

```python
marks = int(input("Enter marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
```

---

## 💡 Key Learnings

* Understanding Python basics and syntax
* Writing simple programs using conditions and loops
* Taking user input and processing it
* Building logic for real-world problems

---

🚀 *Completed Day 1 of my Data Science journey with hands-on practice and mini project.*

# 📅 Day 2: Logic Building & Data Thinking

## 🧠 Concepts Covered

### 🔹 Lists

Lists are used to store multiple values in a single variable.
They are widely used in data analysis to represent datasets.

---

### 🔹 Indexing

* Access elements using position
* Index starts from **0**
* `0` → first element
* `-1` → last element

---

### 🔹 List Operations

* Adding elements (`append`)
* Accessing values
* Iterating using loops

---

### 🔹 Multiple Conditions

* `and` → all conditions must be true
* `or` → any one condition must be true

Used in real-world logic like:

* Student pass/fail systems
* Eligibility checks

---

## 💻 Hands-on Practice

### 🔥 Task 1: List Creation

```python id="6xq9kv"
numbers = [10, 20, 30, 40, 50]

print("First element:", numbers[0])
print("Last element:", numbers[-1])
```

---

### 🔥 Task 2: Sum of List

```python id="c9dz4n"
numbers = [10, 20, 30, 40, 50]

total = 0
for num in numbers:
    total += num

print("Sum:", total)
```

---

### 🔥 Task 3: Maximum Number

```python id="5z5g2r"
numbers = [10, 25, 5, 60, 30]

max_num = numbers[0]

for num in numbers:
    if num > max_num:
        max_num = num

print("Max:", max_num)
```

---

### 🔥 Task 4: Student Pass System

```python id="4v7l3s"
m1 = int(input("Enter marks 1: "))
m2 = int(input("Enter marks 2: "))
m3 = int(input("Enter marks 3: "))

if m1 >= 50 and m2 >= 50 and m3 >= 50:
    print("Pass")
else:
    print("Fail")
```

---

### 🔥 Task 5: Count Even Numbers

```python id="x8v6y1"
numbers = [1, 2, 3, 4, 5, 6]

count = 0

for num in numbers:
    if num % 2 == 0:
        count += 1

print("Even count:", count)
```

---

## 🧠 Analytical Thinking

* Data is represented as **lists**
* Analysis is done using **loops + conditions**

Examples:

* Counting values
* Finding maximum/minimum
* Calculating totals and averages

---

## 💡 Key Learnings

* Working with collections of data (lists)
* Applying logic using loops and conditions
* Solving real-world problems using Python
* Understanding the foundation of data analysis

---

🚀 *Completed Day 2 focusing on logic building and data analysis thinking.*
