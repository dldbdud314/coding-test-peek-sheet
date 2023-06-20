### 기본

- 길이: `str.length()` 
- 특정 인덱스의 char: `str.charAt(idx)`
- 해당 글자로 시작/끝나는지: `str.startsWith(char)`, `str.endsWith(char)` (-> boolean)

### 문자열 찾기

- 해당 스트링이 등장한 인덱스 반환: `indexOf(str)`, `indexOf(str, startIdx)`(여기서부터 찾아!: ~>)
- 반대 방향으로 찾기: `lastIndexOf(str)`, `lastIndexOf(str, startIdx)` (여기서부터 찾아!: <~)

### 문자열 추출

- `str.substring(startIdx)`
- `str.substring(startIdx, endIdx)`

### 문자열 대체

- `str.replace(beforeStr, afterStr)`

### 문자열 분리

- `str.split(기준 문자)` (-> String[])

### 문자열 합치기
````java
String[] strings = new String[] {"a", "b", "c", "d"};

// 1. String join 메소드
String.join(", ", strings); // a, b, c, d

// 2. stream 활용
strings.stream().collect(Collectors.joining(", ")
````

### meddling

- 모두 소문자로/모두 대문자로: `str.toLowerCase()`, `str.toUpperCase()`

### 같은지/포함됐는지

- `str1.equals(str2)`, `str1.equalsIgnoreCase(str2)`(대소문자 무시)
- `str.contains(str2)`

### 문자열 뒤집기

- `new StringBuilder().reverse().toString()`

### string -> char stream (사실 int stream)

- `str.chars()`
