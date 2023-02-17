## Dictionary

### 요소 접근 

- `d.keys()`
- `d.values()`
- `d.items()` 

### 연산

#### 삭제하기

- `del d[key]` : 해당 key-value 삭제 
- `d.pop(key)` : 해당하는 value 반환 후 삭제

#### 합치기

- `d1.update(d2)` : d1에 d2 추가
- `{**d1, **d2}`

### Counter

- `Counter(lst).most_common()` : 가장 많이 나타난 순으로 리스트, `n = 2`로 개수 지정 가능
