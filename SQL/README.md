#### 집계 함수 : COUNT, SUM, AVG, MIN/MAX

- WHERE 절에 사용 불가, HAVING 절에 가능

#### ORDER BY COL ASC/DESC LIMIT 1

#### BETWEEN A and B

== `val >= A and val <= B`

#### DATE_FORMAT(datetime, '%Y%m%d') = '20220413'

#### SUBSTR(string, from, length)

#### CONCAT_WS(sep, string1, string2, ...)

#### CASE

````sql
CASE NAME
  WHEN 'Dog' THEN '개'
  WHEN 'Cat' THEN '고양이'
  ELSE '알수없음'
END
````

````sql
CASE
  WHEN name LIKE '%Dog%' THEN '개'
  WHEN name LIKE 'Cat' THEN '고양이'
  ELSE '알수없음'
END
````

#### ABS(number)

#### CEIL(num, at) / FLOOR(num, at) / ROUND(num, at)

: num을 at 자릿수 기준 올림/내림/반올림

