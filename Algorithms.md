
```python
print("문장1", "문장2")  # O(1) 시간복잡도, O(1) 공간복잡도
# 두 문자열 독립적 출력
print("문장1 문장2")  # O(1) 시간복잡도, O(1) 공간복잡도
# 단일 문자열 출력
'''
- 상수 시간 및 공간 복잡도 측면에서 두 방법 모두 효율적.
- 하지만 실행 방식에서 1번째가 메모리 사용을 최소화하고 동적 문자열 생성 시 더 효율적.
'''

print("문장1" + " " + "문장2")  # O(n) 시간복잡도, O(n) 공간복잡도
'''
- 두 문자열을 합치는 작업 자체가 추가 작업이기 때문에 시간복잡도가 O(n)으로 증가한다.
- 새로운 문자열이 생기기 때문에 메모리가 더 필요하므로 공간복잡도가 O(n)으로 증가한다.
'''
```

```python
# 기존 코드
a = input()
b = input()
print(a)
print(b)

# 효율성은 미미하게 더 좋지만 가독성이 더 뛰어난 코드
print(input(), input(), sep="\n")
```
```python
# 기존 코드
a = input()
b = input()
print(b,a,sep='\n')

#미미한 메모리 사용량 증가, 그러나 뛰어난 가독성과 추후 수정 친화적
def get_and_print_reversed_inputs():
    a = input("Enter the first input: ")
    b = input("Enter the second input: ")
    print("Second input:", b)
    print("First input:", a)

get_and_print_reversed_inputs()
```