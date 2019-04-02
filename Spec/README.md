## Spec

### 자료형

#### Primitive
- `int` : 32비트 정수
- `i64` : 64비트 정수
- `double` : 실수
- `string` : 문자열
- `T[]` : 배열(정적 배열)

#### Data structure
- `vec<T>` : 가변 길이 배열
- `tree<V>` or `tree<V, E>` : 트리 (정점 정보 V, 엣지 정보 E)
- `graph<V, E>` : 무향 그래프 (정점 정보 V, 엣지 정보 E)
  - `digraph<V, E>` : 유향 그래프
  - `netgraph<V, E>` : 플로우(capacity) 그래프
- `matrix<int>` or `matrix<double>` : 행렬
- `disjoint_set<V>` : 상호배타적 집합 (정점 정보 V)
- `set<T>` : BST 기반 셋
- `map<K, V>` : BST 기반 맵
- `hash_set<T>` : 해시 셋
- `hash_map<K, V>` : 해시 기반 맵
- `seg_tree<T>` : 세그먼트 트리

변수 선언은 `(자료형) (변수명)`


### 입출력

- input() : 입력 수행. 변수 선언시, `(자료형) a, b, c, ... = input()` 꼴로 받을 경우 순서대로 해당 변수들을 입력받아서 초기화시킨다. 인자로 정수를 받을 수 있으며, 이 때는 각 변수 하나당 해당 인자 개수 만큼 값을 넣는다(배열 등)
  - example - 길이 n 배열 두개 입력 : `vec<int> arr1, arr2 = input(n)`
- output(value) : 인자로 들어 온 출력 수행. 배열의 경우 구분자를 넣을 수 있다. 생략시 공백.

### 알고리즘

- sort
- binary_search(arr, value, match) : 주어진 정렬된 배열에서 match 조건 만족하는 값 찾는다. match 생략시 ==으로 비교
- parametric_max(lo, hi, match) : lo ~ hi 범위에서 match 해당하는 최댓값. 없으면 hi + 1
- parametric_min(lo, hi, match) : lo ~ hi 범위에서 match 해당하는 최솟값. 없으면 lo - 1
