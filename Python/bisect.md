### bisect_left, bisect_right

> 정렬된 리스트에 v값이 들어갈 자리의 인덱스 값을 반환

- `bisect_left(lst, v)`: 정렬된 lst에 v가 추가될 가장 왼쪽 인덱스 RETURN
- `bisect_right(lst, v)`: 정렬된 lst에 v가 추가될 가장 오른쪽 인덱스 RETURN

### 응용: count_by_range

````python
from bisect import bisect_left, bisect_right

# lst에서 lv <= x <= rv인 원소 개수 반환하기
def count_by_range(lst, lv, rv):
  r_idx = bisect_right(lst, rv)
  l_idx = bisect_left(lst, lv)
  
  return r_idx - l_idx
````

### insort

> 정렬된 리스트에 v값을 추가함

- `insort_left(lst, v)`
- `insort_right(lst, v)`
