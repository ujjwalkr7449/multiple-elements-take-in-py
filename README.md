# multiple-elements-take-in-py
# Python List Input – Multiple Values

## 📌 Description
This program demonstrates how to take multiple inputs from the user and store them in a Python list using `input()`, `split()`, `map()`, and `list()`.

## 💻 1. Multiple Integer Inputs

```python
numbers = list(map(int, input("Enter numbers: ").split()))

print("Numbers:", numbers)
```

### Example

**Input:**
```text
Enter numbers: 10 20 30 40 50
```

**Output:**
```text
Numbers: [10, 20, 30, 40, 50]
```

## 📖 2. Understanding the Code

- `input()` – Takes input from the user.
- `split()` – Separates values using spaces.
- `map(int, ...)` – Converts each input value into an integer.
- `list()` – Stores the values in a list.

## 💻 3. Multiple String Inputs

```python
names = input("Enter names: ").split()

print("Names:", names)
```

**Input:**
```text
Enter names: Ujjwal Rahul Aman
```

**Output:**
```text
Names: ['Ujjwal', 'Rahul', 'Aman']
```

## 💻 4. Take Input Using a Loop

```python
n = int(input("How many numbers? "))

numbers = []

for i in range(n):
    value = int(input("Enter number: "))
    numbers.append(value)

print("Numbers:", numbers)
```

## 🧠 Practice Questions

1. Find the sum of all numbers in a list.
2. Find the largest number in a list.
3. Find the smallest number in a list.
4. Count the even numbers in a list.
5. Count the odd numbers in a list.
6. Reverse a list.
7. Remove duplicate values from a list.

## 🎯 Key Learning

Learn how to accept multiple user inputs, convert data types, store values in lists, and prepare for Python logical programming and coding interviews.

## 🛠️ Technology

- Python 3

## 👨‍💻 Author

Ujjwal Kumar
