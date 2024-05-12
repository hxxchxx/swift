## ::Int, UInt::

- Int는 정수 타입. 기본적으로 64비트 정수형
- UInt는 양의 정수 타입. 기본적으로 64비트 양의 정수형.
- 예시: Int

```swift
// Int
var someInt: Int = -100
// someInt = 100.1 // 컴파일 오류발생
```

- 예시: UInt

```swift
//UInt
var someUInt: UInt = 100
// someUInt = -100 // 컴파일 오류발생
// someUInt = someInt // 컴파일 오류발생
```