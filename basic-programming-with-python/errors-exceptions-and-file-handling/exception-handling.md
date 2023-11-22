```python
def divide_by(a, b):
  return a / b

try:
  ans = divide_by(40, 0)
except Exception as e:
  print("Something went wrong!", e)
  print(e.__class__)
```
```python
def divide_by(a, b):
  return a / b

try:
  ans = divide_by(40, 0)
except ZeroDivisionError as e:
  print(e, "we cannot divide by zero")
```
```python
def divide_by(a, b):
  return a / b

try:
  ans = divide_by(40, 0)
except ZeroDivisionError as e:
  print(e, "we cannot divide by zero")
except Exception as e:
  print(e, "something went wrong")
```
