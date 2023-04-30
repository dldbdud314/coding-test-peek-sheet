### 단순 Queue

````java
Queue<String> queue = new LinkedList<String>();

queue.isEmpty();

// 데이터 삽입
queue.offer("one");
queue.offer("two");
queue.offer("three");

// 맨앞에 위치한 값 보기 
String front = queue.peek();  // front = "one"

// 맨앞 데이터 빼기
String front = queue.poll();  // queue : "two", "three"

// 덱: 양방향 큐 
Deque<Integer> deque = new LinkedList<Integer>();

deque.offerFirst(1);
deque.offerLast(2);
deque.offerFirst(3);
deque.offerFirst(4);

deque.pollFirst();
deque.pollLast();
````

### PriorityQueue

````java
Queue<Integer> MinHeap = new PriorityQueue<>();
Queue<Integer> MaxHeap = new PriorityQueue<>(Comparator.reverseOrder());
