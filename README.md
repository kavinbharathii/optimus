# Optimus
A python package to document and log the performance times between two functions in python.

### Installation:
On windows machines,
```
$ pip install optimus_py
```
On unix systems,
```
$ pip3 install optimus_py
```

### Usage:
Example code:

```python
def foo(x, y):
    return x + y
    
def bar(x):
    return x**2
```

To use optimus,
```python
from optimus import optimus_compare as op

op('foo', 'bar', (10, 20), (5, ))
```

