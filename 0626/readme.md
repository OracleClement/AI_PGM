# 파이썬 리스트

## 1. 리스트란?
파이썬 리스트(list)는 여러 값을 하나의 변수에 저장할 수 있는 자료형입니다. 값의 순서가 있으며, 내용을 바꿀 수 있는 **가변** 자료형입니다. 숫자, 문자열, 불리언처럼 서로 다른 타입을 함께 넣을 수도 있습니다.

## 2. 리스트 생성
리스트는 대괄호 `[]`로 만듭니다.

```python
a =[3][4][1]
b = ["apple", "banana", "cherry"]
c = [1, "hello", True]
```

## 3. 리스트의 특징
- 순서가 있습니다.
- 중복 값을 허용합니다.
- 서로 다른 자료형을 함께 저장할 수 있습니다.
- 생성 후에도 값을 수정할 수 있습니다.

## 4. 인덱싱과 슬라이싱
리스트의 각 원소는 인덱스로 접근합니다. 파이썬은 0부터 시작합니다.

```python
lst =[5][6]
print(lst)   # 10
print(lst)   # 30[1]
print(lst[-1])  # 50
print(lst[1:4]) #[5]
```

- `lst[0]`은 첫 번째 원소입니다.
- `lst[-1]`은 마지막 원소입니다.
- `lst[start:end]`는 범위를 잘라냅니다.

## 5. 값 추가하기
리스트에 값을 추가하는 방법은 여러 가지가 있습니다.

```python
lst =[4][3][1]
lst.append(4)
lst.insert(1, 10)
lst.extend()[7][8]
print(lst)
```

- `append(x)`: 맨 뒤에 하나 추가합니다.
- `insert(i, x)`: 원하는 위치에 삽입합니다.
- `extend(iterable)`: 여러 값을 한 번에 추가합니다.

## 6. 값 삭제하기
리스트에서 값을 삭제하는 방법도 다양합니다.

```python
lst =[9][3][4][7][1]
lst.pop()
lst.remove(2)
del lst
print(lst)
```

- `pop()`: 마지막 값을 꺼내고 삭제합니다.
- `remove(x)`: 값이 `x`인 첫 번째 항목을 삭제합니다.
- `del`: 인덱스나 슬라이스를 삭제할 수 있습니다.

## 7. 자주 쓰는 함수와 메서드
- `len(lst)`: 리스트 길이를 구합니다.
- `min(lst)`: 가장 작은 값을 구합니다.
- `max(lst)`: 가장 큰 값을 구합니다.
- `sum(lst)`: 숫자 리스트의 합을 구합니다.
- `sort()`: 리스트를 정렬합니다.
- `reverse()`: 리스트 순서를 뒤집습니다.

```python
nums =[3][4][7][9]
print(len(nums))
print(min(nums))
print(max(nums))
print(sum(nums))
nums.sort()
print(nums)
```

## 8. 반복문과 리스트
리스트는 반복문과 함께 자주 사용됩니다.

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

이렇게 하면 리스트의 각 원소를 하나씩 순서대로 처리할 수 있습니다.

## 9. 리스트 컴프리헨션
리스트 컴프리헨션을 사용하면 짧고 간단하게 새 리스트를 만들 수 있습니다.

```python
nums =[4][7][9][1][3]
squares = [x * x for x in nums]
print(squares)
```

- 기존 리스트를 기반으로 새 리스트를 만들 때 유용합니다.
- 코드가 짧고 읽기 쉬워집니다.

## 10. 실전 예제
```python
scores = 
scores.append(88)
scores.sort()
print(scores)
print("평균:", sum(scores) / len(scores))
```

이 예제에서는 점수 목록에 값을 추가하고 정렬한 뒤 평균까지 구합니다.

## 11. 정리
파이썬 리스트는 가장 기본적이면서도 매우 중요한 자료형입니다. 데이터를 모아 저장하고, 수정하고, 반복 처리하는 데 널리 사용됩니다. 파이썬을 배우는 초반부터 꼭 익혀두면 좋은 개념입니다.
