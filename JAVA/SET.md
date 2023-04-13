### 주요 문법들

````java
Set<Integer> set = new HashSet<>();

set.add(1);
set.add(4);

set.remove(40);

set.size();

set.contains(10);

// 부분집합인지 판별하기
Set<Integer> setA = new HashSet<>(Arrays.asList(1, 2, 3, 4, 5));
Set<Integer> setB = new HashSet<>(Arrays.asList(3, 4, 5));
setA.containsAll(setB)  // setB의 모든 요소가 setA의 부분집합인가? -> true

// 합집합 : SetA + SetB
Set<Integer> setA = new HashSet<>(Arrays.asList(1, 2));
Set<Integer> setB = new HashSet<>(Arrays.asList(3, 4, 5));
setA.addAll(setB)  // setA = {1, 2, 3, 4, 5}

// 차집합 : SetA - SetB
Set<Integer> setA = new HashSet<>(Arrays.asList(1, 2, 3, 4, 5));
Set<Integer> setB = new HashSet<>(Arrays.asList(3, 4, 5));
setA.removeAll(setB)  // setA = {1, 2}

// 교집합 : SetA & SetB
Set<Integer> setA = new HashSet<>(Arrays.asList(1, 2, 3, 4));
Set<Integer> setB = new HashSet<>(Arrays.asList(3, 4, 5));
setA.retainAll(setB)  // setA = {3, 4}
````
