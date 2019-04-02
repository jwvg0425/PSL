## Spec

### 자료형

#### Primitive
- int : 32비트 정수
- i64 : 64비트 정수
- double : 실수
- string : 문자열
- T[] : 배열(정적 배열)

#### Data structure
- vec<T> : 가변 길이 배열
- tree<V> or tree<V, E> : 트리 (정점 정보 V, 엣지 정보 E)
- graph<V, E> : 무향 그래프 (정점 정보 V, 엣지 정보 E)
  - digraph<V, E> : 유향 그래프
  - netgraph<V, E> : 플로우(capacity) 그래프
- matrix<int> or matrix<double> : 행렬
- disjoint_set<V> : 상호배타적 집합 (정점 정보 V)
- set<T> : BST 기반 셋
- map<K, V> : BST 기반 맵
- hash_set<T> : 해시 셋
- hash_map<K, V> : 해시 기반 맵
- seg_tree<T> : 세그먼트 트리
