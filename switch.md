- 명시적 break를 하지 않아도 자동으로 case마다 break 됨
- 구조

```swift
switch 비교값 {
case 패턴:
    /* 실행 구문 */
default:
    /* 실행 구문 */
}
```

- 예시

```swift
var m = "a"
switch m {
    case "a","e","i","o","u":
        print("\\(m)는모음");
    case "a"..."z":
        print("\\(m)는 자음")
    default:
        print("\\(m)는 모음도 자음도 아니다. 정체가 뭐냐!")
} //a라고 넣었기에 a는 모음 출력
var m = "j"
switch m {
    case "a","e","i","o","u":
        print("\\(m)는모음");
    case "a"..."z":
        print("\\(m)는 자음")
    default:
        print("\\(m)는 모음도 자음도 아니다. 정체가 뭐냐!")
} //j라고 넣었기에 j는 자음 출력
var m = "응"
switch m {
    case "a","e","i","o","u":
        print("\\(m)는모음");
    case "a"..."z":
        print("\\(m)는 자음")
    default:
        print("\\(m)는 모음도 자음도 아니다. 정체가 뭐냐!")
} //응이라고 넣었기에 응는 모음도 자음도 아니다. 정체가 뭐냐! 출력
```