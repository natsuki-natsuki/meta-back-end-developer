## Python dictionary syntax
```python
sample_dict = {1: 'Coffee', 2: 'Tea', 3: 'Juice'}
print(sample_dict[1])

#Coffee

#change
sample_dict[2] = 'Mint Tea'

#delete
del sample_dict[3]

my_d = {}
print(type(my_d))

my_d = {1: 'Test', 'Name: 'Jim'}
print(my_d)

print(my_d[1])

my_d[2] = 'Test 2'
my_d[1] = 'Not a test!'
print(my_d)

my_d = {1: 'Test', 'Name: 'Jim', 1: 'Not a test'}
print(my_d)

del my_d[1]

for x in my_d:
  print(x)

for key, value in my_d.items():
  print(str(key) + ":" + value)

```
