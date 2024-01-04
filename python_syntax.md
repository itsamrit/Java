Certainly! Here's the equivalent code in Python for the given operations on different data types:


1. Dynamic Arrays (List):
```python
a = []
a.append(element)
a.remove(element)
del a[index]
size = len(a)
last = a[i]
```

2. String:
```python
s = "Hello, World!"
temp = str_var
size = len(str_var)
c = str_var[i]
```

3. Char:
```python
c = 'A'
```

5. Stack:
Python doesn't have a built-in implementation of a traditional stack. Lists in Python can be used as stacks

6. Queue:

```python
Python's `deque` can be used as a double-ended queue, Python has queue but its more for complicated task not used for DSA
from collections import deque

q = deque()
q.append(element)
q.popleft()
size = len(q)
front = q[0]
```

7. Deque:
```python
from collections import deque

deque_var = deque()
deque_var.appendleft(element)
deque_var.append(element)
deque_var.popleft()
deque_var.pop()
first = deque_var[0]
last = deque_var[-1]
size = len(deque_var)
```

8. Priority Queue (using heapq):
```python
import heapq

# Example of Min-Heap
min_heap = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5]
heapq.heapify(min_heap)
print("Min-Heap:", min_heap)

# Example of Max-Heap (by negating values)
max_heap = [-x for x in min_heap]
heapq.heapify(max_heap)
print("Max-Heap:", [-x for x in max_heap])

# Inserting into Min-Heap
heapq.heappush(min_heap, 0)
print("After inserting 0 into Min-Heap:", min_heap)

# Inserting into Max-Heap (by negating value)
heapq.heappush(max_heap, -7)
print("After inserting -7 into Max-Heap:", [-x for x in max_heap])

# Popping from Min-Heap
min_value = heapq.heappop(min_heap)
print(f"Popped from Min-Heap: {min_value}, Updated Min-Heap: {min_heap}")

# Popping from Max-Heap (by negating value)
max_value = -heapq.heappop(max_heap)
print(f"Popped from Max-Heap: {max_value}, Updated Max-Heap: {[-x for x in max_heap]}")

```

9. Map (Dictionary):
```python
m = {}
m[key] = value
m.pop(key, None)
size = len(m)
if key in m:
    value = m[key]
```

10. Set:
```python
s = set()
s= set(listName)
s.add("Element1")
s.remove("Element2")
size = len(s)
iterator = iter(s)
if next(iterator, None) is not None:
    first_element = next(iterator)
if target_element in s:
    # Do something
```

Note: Python dictionaries can be used as maps.
