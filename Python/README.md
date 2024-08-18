## itertools

```python
# 순열
from itertools import permutations
# 조합
from itertools import combinations

# 참고용
# 중복 순열
from itertools import product
# 중복 조합
from itertools import combinations_with_replacement
```

## heapq

```python
from heapq import heappush, heappop

# min heap만 지원된다
# max heap 야매로 구현하려면
heappush(q, -x)
biggest = -heappop(q)
```

## bisect

정렬된 리스트에서 특정 원소 찾기 좋다

```python
from bisect import bisect_left, bisect_right
```

## collections

```python
from collections import deque
from collections import defaultdict
```
