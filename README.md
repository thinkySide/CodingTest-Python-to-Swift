# CodingTest-Python-to-Swift
코딩 테스트 합격자 되기 - 파이썬편을 읽으며 풀이한 문제를 Swift로 옮겨 정리합니다!

## A. 배열 List
- 중복이라는 키워드가 나오면 `Set`을 활용해보자!
- 중간에 데이터를 삽입할 일이 많다면 배열은 비효율적이다. 다른 방법을 생각해보자.
- 많이 사용했던 함수: `enumerated()`, `indicies`, `filter`, `map`, `compactMap`, `sorted`, `reversed` `abs`

#### Day 01 - 24.07.24
- [01. 배열 정렬하기](배열/01_배열%20정렬하기.md)
- [02. 배열 제어하기](배열/02_배열%20제어하기.md)
- [03. 두 개 뽑아서 더하기](배열/03_두%20개%20뽑아서%20더하기.md)

#### Day 02 - 24.07.26
- [04. 모의고사](배열/04_모의고사.md) 
- [05. 행렬의 곱셈](배열/05_행렬의%20곱셈.md)

#### Day 03 - 24.07.29
- [06. 실패율](배열/06_실패율.md)

#### Day 04 - 24.07.31
- [07. 방문 길이](배열/07_방문%20길이.md)

## B. 스택 Stack
- 가장 가까운, 최근이라는 키워드를 보고 스택을 연상시킬 수도 있을 것.
- 배열에 직접 추가, 삭제, 이동은 많은 비용을 발생시킨다. (인덱스를 이용하는 방법으로 접근해 볼 것)
- 많이 사용했던 함수: `removeLast`, `Array(repeating:count)`

#### Day 05 - 24.12.23
- [08. 괄호 짝 맞추기](스택/08_괄호%20짝%20맞추기.md)
- [09. 10진수를 2진수로 변환하기](스택/09_10진수를%202진수로%20변환하기.md)

#### Day 06 - 24.12.24
- [10. 괄호 회전하기](스택/10_괄호%20회전하기.md)

#### Day 07 - 24.12.25
- [11. 짝지어 제거하기](스택/11_짝지어%20제거하기.md)
- [12. 주식 가격](스택/12_주식%20가격.md)

#### Day 08 - 24.12.26
- [13. 크레인 인형 뽑기 게임](스택/13_크레인%20인형%20뽑기%20게임.md)
- [14. 표 편집](스택/14_표%20편집.md)

## C. 큐 Queue
- 전체적인 구조는 스택과 비슷하다.
- 원형 큐는 front와 rear가 도는 형태.
- 순서는 유지하되, 앞이 뒤보다 먼저 선행되어야 하는 곳에서 활용하기 좋음.
- 덱은 `Double Ended Queue`의 줄임말이다. (양 끝에서 삽입 및 삭제가 가능한 큐)

#### Day 09 - 24.12.28
- [15. 요세푸스 문제](큐/15_요세푸스%20문제.md)
- [16. 기능 개발](큐/16_기능%20개발.md)

#### Day 10 - 24.12.29
- [17. 카드 뭉치](큐/17_카드%20뭉치.md)

## D. 해시 Hash
- 키와 값을 매칭하여 O(1)로 찾을 수 있기 때문에, 시간복잡도 측면에서 유리하다.
- 하지만 해싱함수를 구현할 때 충돌이 나거나(서로 다른 키가 같은 값을 가리킴) 메모리 공간을 크게 사용할 수 있음을 염두에 두자.
- `Dictionary`를 사용해 쉽게 해시를 구현할 수 있다.

#### Day 11 - 24.12.30
- [18. 두 개의 수로 특정값 만들기](해시/18_두%20개의%20수로%20특정값%20만들기.md)
- [19. 문자열 해싱을 이용한 검색 함수 만들기](해시/19_문자열%20해싱을%20이용한%20검색%20함수%20만들기.md)

#### Day 12 - 24.12.31
- [20. 완주하지 못한 선수](해시/20_완주하지%20못한%20선수.md)
- [21. 할인 행사](해시/21_할인%20행사.md)

#### Day 13 - 25.01.01
- [22. 오픈채팅방](해시/22_오픈채팅방.md)
- [23. 베스트 앨범](해시/23_베스트%20앨범.md)

#### Day 14 - 25.01.02
- [24. 신고 결과 받기](해시/24_신고%20결과%20받기.md)
- [25. 메뉴 리뉴얼](해시/25_메뉴%20리뉴얼.md)

## E. 트리 Tree
- 대부분의 코딩테스트 문제를 풀 때에는 이진 트리(간선이 최대 2개인 트리) 정도만 알아도 가능하다.
- 모든 탐색 알고리즘에서 탐색 효율을 개선하는 방법은 "탐색 대상이 아닌 노드를 한 번에 많이 제외하는 것"
- 트리의 균형이 맞으면 O(logN), 균형이 안맞는 최악의 상황에선 O(N)의 시간복잡도를 가진다.

#### Day 15 - 25.01.10
- [26. 트리 순회](트리/26_트리%20순회.md)
- [27. 이진 탐색 트리 구현](트리/27_이진%20탐색%20트리%20구현.md)
