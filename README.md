# 🏹 Algorithm_MT (0725 ~ 0811)

### [1. 알고리즘? 코딩테스트?](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%201DAY.md)
    * 알고리즘 : 어떤 문제를 해결하기 위해 정해진 일련의 절차나 행동
    * 코딩테스트 : 기업에서 지원자를 대상으로 코딩을 통한 문제해결 기반 문제 해결 능력을 테스트 하는 것

✔ 문제해결력 : 문제 의도를 정확히 파악하고, 적절한 해결 방법을 적용할 수 있는가?

✔ 구현력 : 해결 방법을 프로그래밍을 통해 능숙하게 구현할 수 있는가? (규칙들을 어떻게 접근할 것인지)

> 코딩테스트 - ( 문제파악, 해결 방법 구상, 정답 구현 )


> 현업 - (비즈니스 문제 발생, 해결 방법 구상, 구현 및 수정 )

---

### [2. 코딩테스트 종류](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%201DAY.md)
    * 온라인, 오프라인, 기업
    
📢 온라인 코딩테스트 TIP

- 사전에 연습장과 필기도구 준비 (마음 급하게 코드부터 치지 않을 것 )

- 테스트 케이스 이외의 엣지 케이스도 확인

- 인터넷, IDE, 알고리즘 노트 적극 활용

---

### [3. 코딩테스트 준비하기](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%201DAY.md)

#### (⭐많이 풀기(정말 많이 풀기(진짜 많이풀기⭐)⭐)⭐)

    🤔 문제는 매번 풀때마다 다르유형을 푸는 것이 좋다? : X
    
    🤔 오랜 시간 고민했는데 풀리지 않을 때, 끝까지 답을 보지 않는 것이 좋다? : X

    🤔 알고리즘 문제는 몇문제 정도 풀어야 할까? : 약 300~350문제



📢 기타 꿀TIP

- 변수명 대충 짓지 낳기

- 언어가 가지는 내장함수, 라이브러리를 적극 활용하기

- 반복되는 코드는 함수화를 통해 가독성 있게 작성하기

- 면접을 위해 풀이를 남에게 설명하는 연습 반드시 필요

---

### [4. 데이터 구조와 알고리즘](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%201DAY.md)

> 👩‍🔬 Niklaous Wirth 프로그램 = 데이터 구조 + 알고리즘

> 물통 == 물 + 통 / 데이터 구조 == 데이터 +구조

코딩 테스트 정복을 위한 데이터 구조와 알고리즘

: Array 배열, Linked List 연결 리스트, Hash 해시, Stack 스택, Queue 큐, Priority Queue 우선순위 큐

Heap 힙 Tree 트리, Graph 그래프

[기본] : 완전탐색, 재귀, 시뮬레이션, 그리디

[심화] : DFS, BFS, 백트래킹, 이진탐색, DP, 다익스트라, 크루스칼, 프림

- 데이터 구조
: 리스트, 문자열, 딕셔너리, 스택, 큐, 그래프

- 알고리즘
: 재귀, 완전탐색, 시뮬레이션, 깊이우선탐색(DFS), 너비우선탐색(BFS), 백트래킹

---

### [✍ Chapter 1. 시간 복잡도 & 빅오표기법](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%202DAY.md) 

#### (1) Time Complexity 시간 복잡도 

> input을 넣은 후 output이 나오는 시간이 짧은 알고리즘이 좋은 알고리즘 

```python
def count(word, char):
	total = 0 
	
	for i in word:
		if i == chr:
			total += 1
			
	return total 
	
# 기본 연산 : 단위 시간 1이 소요되는 시간 
# ⭐기본 연산의 총 횟수 == 알고리즘의 소요시간 
```
      시간 복잡도가 높다 => 느린 알고리즘
   
      시간 복잡도가 낮다 => 빠른 알고리즘
      
      
◻ 복잡한 정도 

![image](https://user-images.githubusercontent.com/99783474/184548337-75a3b6d9-3305-430d-8415-d5f256a0b9f5.png)


#### (2) Big-O 빅오표기법 

![image](https://user-images.githubusercontent.com/99783474/184548438-c6f8b25e-d29e-412b-a1c6-8889fcfd5eff.png)

---

### [✍ Chapter 2. List 리스트](https://github.com/oiosu/Algorithm_MT/blob/main/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98_%EA%B0%9C%EB%85%90/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%202DAY.md) 

#### (1) Array 배열 VS Linked List 연결리스트 

| Array 배열                                                   | Linked List 연결 리스트                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 요일마다 먹는 약통💊을 생각해 보자                            | 데이터가 담긴 여러 노드들이 순차적으로 연결된 형태의 자료구조 |
| **여러 데이터들이 연속된 메모리 공간에 저장되어 있는 자료구조** | 맨처음 노드부터 순차적으로 탐색                              |
| 인덱스를 통해 데이터에 빠르게 접근                           | 연결 리스트의 길이 자유롭게 변경 가능 => 삽입, 삭제가 편리   |
| 배열의 길이는 변경이 불가능 => 길이를 변경하고 싶다면 새로 생성 | 다양한 데이터 타입 저장                                      |
| 데이터 타입은 고정                                           | 데이터가 메모리에 연속적으로 저장되지 않음                   |


#### (2) 파이썬의 리스트

	 .append(원소) : 리스트 맨 끝에 새로운 원소 삽입
	 .pop(인덱스) : 특정 인덱스에 있는 원소를 삭제 및 반환 
	 .count(원소) : 리스트에서 해당 원소의 개수를 반환 
	 .index(원소) : 리스트에서 처음으로 원소가 등장하는 인덱스 반환
	 .sort() : 리스트를 오름차순으로 정렬 (reverse = True 옵션을 통해 내림차순으로 정렬가능 )
	 .reverse() : 리스트의 원소들의 순서를 거꾸로 뒤집기 
	 len(iterable) : 리스트의 길이(원소의 개수)를 반환
	 sum(iterable) : 리스트의 모든 원소의 합을 반환 
	 max(iterable) & min(iterable) : 리스트의 원소 중 최대 & 최소값을 반환
	 sorted(iterable) : 오름차순으로 정렬된 새로운 리스트 반환 (반환 리스트는 변화 없음)
	 reversed(iterable)  : 리스트의 순서를 거꾸로 뒤집은 새로운 객체 반환 (원본 리스트는 변화 없음 )


