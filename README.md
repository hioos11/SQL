# SQL

### 정렬하기
ORDER BY 컬럼 ASC / DESC
- ASC : 오름차순. 기본값. 생략 가능
- DESC : 내림차순

#### 조건식이 있는 경우의 정렬
SELECT * FROM 테이블 WHERE 조건식 ORDER BY 컬럼


### LIMIT
- limit a : a개의 컬럼 가져옴
- limit a, b : a번째부터 b개 가져옴 (첫번째 컬럼은 0부터 시작)

ex) SELECT DATETIME from ANIMAL_INS ORDER BY DATETIME DESC limit 1
DATETIME을 내림차순으로 정렬 후 최상단 데이터 가져옴 (가장 최근의 DATETIME)
