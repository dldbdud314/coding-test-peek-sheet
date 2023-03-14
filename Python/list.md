### methods

- `arr.reverse()`
- `list.count(찾는 값)` / `str.count(찾는 값)`

### list comprehension

#### 짝수번째 인덱스만 담은 리스트 

- `seq = [x for i, x in enumerate(sequence) if i % 2 == 0]`

#### 짝수번째 인덱스에 -1을 곱한 리스트 생성하기

- `seq = [x * (-1) if i % 2 == 0 else x for i, x in enumerate(sequence)]`
