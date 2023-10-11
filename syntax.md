describe how to declare, add , remove and determine size in  java  of following datatypes array , dynamic array , string , char , stack , queue, deque, priority queue, map
  
### 1. Arrays:
```
dataType[] arrayName = new dataType[size];
int size = array.length;
```

### 2. Dynamic Arrays (ArrayList):
```
ArrayList<dataType> listName = new ArrayList<>();
list.add(element);
list.remove(element);
list.remove(index);
int size = list.size();
```

### 3. String:
```
String str = "Hello, World!";
int size = str.length();
```

### 4. Char:
```
char ch = 'A';
```

### 5. Stack:
```
Stack<dataType> stack = new Stack<>();
stack.push(element);
int poppedElement = stack.pop();
int size = stack.size();
```

### 6. Queue:
```
Queue<dataType> queue = new LinkedList<>();
queue.offer(element);
int dequeuedElement = queue.poll();
int size = queue.size();
```

### 7. Deque:
```
Deque<dataType> deque = new LinkedList<>();
deque.addFirst(element);
deque.addLast(element);
int removedFromFront = deque.removeFirst();
int removedFromEnd = deque.removeLast();
int size = deque.size();
```

### 8. Priority Queue:
```
PriorityQueue<dataType> priorityQueue = new PriorityQueue<>();
priorityQueue.offer(element);
int removedElement = priorityQueue.poll();
int size = priorityQueue.size();
```

### 9. Map:
```
Map<KeyType, ValueType> map = new HashMap<>();
map.put(key, value);
map.remove(key);
int size = map.size();
```
