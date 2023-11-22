## Args and kwargs

### args
```python
def sum_of(a, b):
  return a + b

print(sum_of(4, 5))

def sum_of(*args):
  sum = 0
  for x in args:
    sum += x
  return sum

print(sum_of(4, 5, 6))

```

### kwargs key word args
```python
def sum_of(**kwargs):
  sum = 0
  for k, v in kwargs.items():
    sum += v
  return round(sum, 2)

print(sum_of(coffee=2.99, cake=4.55, juice=2.99))

```
