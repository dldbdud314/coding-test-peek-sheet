## Queue

````java
Queue<String> queue = new LinkedList<String>();

// 데이터 삽입
queue.offer("one");
queue.offer("two");
queue.offer("three");

// 맨앞에 위치한 값 보기 
String front = queue.peek();  // front = "one"

// 맨앞 데이터 빼기
String front = queue.poll();  // queue : "two", "three"
