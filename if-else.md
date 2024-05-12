- if만 단독으로 사용해도되고, else, else if 와 조합해서 사용 가능
- if 뒤의 조건 값에는 Bool 타입의 값만 위치해야 함
- 조건을 감싸는 소괄호는 선택사항 (하고 싶으면 소괄호 씀)
- 예시

```swift
let someInteger = 100

if someInteger < 100 {
    print("100 미만")
} else if someInteger > 100 {
    print("100 초과")
} else {
    print("100")
} //100 출력
let someInteger = 85

if someInteger < 100 {
    print("100 미만")
} else if someInteger > 100 {
    print("100 초과")
} else {
    print("100")
} //100 미만 출력
let someInteger = 125

if someInteger < 100 {
    print("100 미만")
} else if someInteger > 100 {
    print("100 초과")
} else {
    print("100")
} // 100 초과 출력
```