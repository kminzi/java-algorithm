# Algorithm_Java
Java로 알고리즘 문제들을 풀어보고 자주 사용되는 자료구조를 정리

### 자료구조
- Array 
  - 길이를 동적으로 변경할 수 없음
- ArrayList
    - List 인터페이스를 구현한 Collection 구현체
    - 가변적으로 리스트 길이 변경 가능
    - 내부적으로 데이터의 추가, 삭제를 위해서는 임시 배열을 생성해 데이터를 복사가 필요하다
    - 추가, 삭제가 많은 경우 그만큼의 데이터 복사가 일어나서 성능 저하가 될 수 있음
    - 각 데이터가 인덱스를 가지고 있어 데이터 검색에는 효율적임
    
- LinkedList
    - List 인터페이스를 구현한 Collection 구현체
    - 데이터를 저장하는 노드가 이전 노드와 다음 노드만 알고 있는 구조 
    - 가변적으로 리스트 길이 변경 가능
    - 검색 시 모든 요소를 탐색해야해서 최악의 경우 O(N)까지 가짐
    - 데이터의 추가, 삭제는 이전/다음 노드만 고려하면 되기 때문에 효율적임
    
    
  
### BOJ

### 프로그래머스
#### 해시
1. ㅇㅇ번 ㅇㅇ
[풀이](./src/programmers/Solution_moreSpicy.java)
