# Algorithm_for_Coding_Test



### <b>알고리즘 공부용 코드 기록
> 나동빈님 이코테2021 기반

* 코드 공부 휴대성을 위해 단순히 코드를 git에 올렸음
* 폴더명도 구분의 편의를 위해 한글로 적었고, 실행에는 문제가 있음
* 코드 기반은 JAVA
  

<hr>


### 목록 가이드
> 기본적인 목차는 동빈님의 강의 목차를 따름(1장은 파이썬 가이드라 목록에 안 넣음)
  

#### 2. 그리드 알고리즘
#### 3. 구현
#### 4. DFS(깊이우선) & BFS(넓이우선)
#### 5. 정렬 이론(SORT)
#### 6. 이진검색트리(Binery Searching Tree)
#### 7. 다이나믹 프로그래밍(DP)

* TOP DOWN
  > 재귀함수를 통해 DP행렬을 채워서 답을 찾는 방식 
* BOTTOM TOP  
  > 반복문 FOR를 통해 DP행렬을 채워서 답을 찾는 방식  
* 행렬 A1 ~ An까지 곱셈과정에서 최소곱셈횟수를 구하기
  > 결합법칙을 통해 구할수 있는 곱셈횟수 중 최소의 곱셈횟수 구하기
  * 풀이 1) 대각선형 DP갱신
  * 풀이 2) 1번 행부터 열의 맨 끝 ~ 맨 위까지 훍고가는 DP 갱신
  
* 최장 공통 부분 문자열(LCS) 판별 알고리즘 
  > 정확한 순서 상관없이 두 문자열 간 진행방향 대비 공통으로 등장하는 문자열들이 무엇인지 모두 판별하는것 
* 배낭에 물건을 최대가치로 넣기(Knapsack)
  > 배낭 감당가능 무게가 존재하고, 물건들의 가치와 무게가 나오면, 거기서 최대한 높은 가치를 챙기는 물건들을 고르는 알고리즘
  
#### 8. 최단거리이론

* 기본 다익스트라 알고리즘
* 개선 다익스트라 알고리즘 (Prior Queue 사용)
* 플로이드 워셜 알고리즘

#### 9. 기타 그래프 이론

* 기본 서로소(Each Other) 판별 알고리즘
* 개선 서로소(Each Other) 판별 알고리즘
* 그래프의 순환여부 체크
  >  서로소 판별 알고리즘에서 출발
* 크루스칼 알고리즘
  > 다익스트라 알고리즘 + 싸이클 판별
* 그래프의 위상 정렬(Topological Sort) 알고리즘
* 기본 최소공통조상(LCA) 찾기
* 개선 최소공통조상(LCA) 찾기

#### 10. 기타 이론

* 소수(Prime Number) 판별 알고리즘
* 에라스토테네스의 체
  > 0~X(지정된 수)까지의 소수 판별 알고리즘
* 기본 배열의 구간 합 구하기 알고리즘(DP 응용) 
* 개선 배열의 구간 합 구하기 알고리즘
  > 2개의 위치 지정 그 사이의 배열값의 합 구하기
* 이진트리를 활용한 구간 합 구하기 알고리즘
  > 2진트리의 2^n으로 뻗어나가는 속성을 구간합에 적용.. 근데 놀랍게도 과정을 봐도 의도한데로 잘 작동한다..

