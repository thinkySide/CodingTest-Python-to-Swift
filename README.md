# CodingTest-Python-to-Swift
코딩 테스트 합격자 되기 - 파이썬편을 읽으며 풀이한 문제를 Swift로 옮겨 정리합니다!

## 배열
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

## 스택
- 가장 가까운, 최근이라는 키워드를 보고 스택을 연상시킬 수도 있을 것.
- 배열에 직접 추가, 삭제, 이동은 많은 비용을 발생시킨다. (인덱스를 이용하는 방법으로 접근해 볼 것)
- 많이 사용했던 함수: `removeLast`, `Array(repeating:count)`

### Day 05 - 24.12.23
- [08. 괄호 짝 맞추기](스택/08_괄호%20짝%20맞추기.md)
- [09. 10진수를 2진수로 변환하기](스택/09_10진수를%202진수로%20변환하기.md)

### Day 06 - 24.12.24
- [10. 괄호 회전하기](스택/10_괄호%20회전하기.md)

### Day 07 - 24.12.25
- [11. 짝지어 제거하기](스택/11_짝지어%20제거하기.md)
- [12. 주식 가격](스택/12_주식%20가격.md)

### Day 08 - 24.12.26
- [13. 크레인 인형 뽑기 게임](스택/13_크레인%20인형%20뽑기%20게임.md)
- [14. 표 편집](스택/14_표%20편집.md)

## 큐
- 전체적인 구조는 스택과 비슷하다.
- 원형 큐는 front와 rear가 도는 형태.
- 순서는 유지하되, 앞이 뒤보다 먼저 선행되어야 하는 곳에서 활용하기 좋음.
- 덱은 `Double Ended Queue`의 줄임말이다. (양 끝에서 삽입 및 삭제가 가능한 큐)

### Day 09 - 24.12.28
- [15. 요세푸스 문제](큐/15_요세푸스%20문제.md)
- [16. 기능 개발](큐/16_기능%20개발.md)
