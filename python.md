# Python Practice Answers

## 1. Make It Shorter

Create a file named `welcome.py` with this code:

```python
def welcome(name):
    return f"Hello, {name}! Welcome to PLP."


print(welcome("Amina"))
print(welcome("Brian"))
print(welcome("Fatuma"))
```

## 2. Your First Toolbox

Create a file named `toolbox.py` with this code:

```python
def double(number):
    return number * 2


def is_pass(score):
    return score >= 50


def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"


print(double(7))
print(double(10))
print(is_pass(80))
print(is_pass(20))
print(greet("Amina"))
print(greet("Brian", "Habari"))
```

## Run in order

1. Save both files in the same folder.
2. Open the terminal in that folder.
3. Run:

```bash
python welcome.py
python toolbox.py
```
