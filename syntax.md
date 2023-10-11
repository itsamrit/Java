describe how to declare, add , remove and determine size and retrieve element in  java  of following datatypes array , dynamic array , string , char , stack , queue, deque, priority queue, map
  
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
int last = arrayList.get(arrayList.size() - 1);
```

### 3. String: Strings are immutable I,e values can't be changed. So use array of chars
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
stack.pop();
int size = stack.size();
int top = stack.peek();
```

### 6. Queue:
```
Queue<dataType> q = new LinkedList<>();  🟩
q.offer(element);
q.poll();
int size = q.size();
int front = q.peek;
```

### 7. Deque:
```
Deque<Integer> deque = new LinkedList<>();  🟩
deque.addFirst(element);
deque.addLast(element);
deque.removeFirst();
deque.removeLast();
deque.size();
```

### 8. Priority Queue:
```
PriorityQueue<dataType> priorityQueue = new PriorityQueue<>();
priorityQueue.offer(element);
priorityQueue.poll();
int size = priorityQueue.size();
```

### 9. Map:
```
Map<KeyType, ValueType> map = new HashMap<>();  🟩
map.put(key, value);
map.remove(key);
int size = map.size();
if(map.containsKey(k))
     map.get(k);

```
