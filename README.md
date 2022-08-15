# CodingStudy_2022
자료구조 & 알고리즘 및 코딩 테스트를 위해 필요한 기본적인 Tip들에 대해 소개한다
- 언어: Python

<br>

## 👍 파이썬 시간복잡도
- 빅오(Big-O) 기준 코드, 메소드, 알고리즘 별 시간복잡도는 다음과 같다.
- cf) 반복문이 병렬로 여러개 있어도 가장 높은 시간복잡도 1개에 대해서만 간주한다

|코드/메소드/알고리즘|시간복잡도|
|---------------|-------|
|for 반복문      |O(N)    |
|이중 for 반복문  |O(N^2)  |
|for 반복문 2개  |O(N)    |

- 리스트 컴프리헨션이 일반 for문보다 속도가 더 빠르다
  - [코드로 알아보는 리스트컴프리헨션이 더 빠른 이유](https://jeongukjae.github.io/posts/inspecting-list-comprehension/)


<br>

## [실행시간 측정]
코드가 전부 실행되는 시간을 체크할 수 있다. (시간단위: 초)

```
import time
start = time.time() # 코드 시작

# 코드 작성

end = time.time() - start
print(end)
```

<br>


## [코드 간결성1]
코드를 작성할 때에는 짧고 명확하며 간결할수록 좋다. 다음에서는 파이썬 코드를 조금 더 간결하게 해줄 수 있는 **리스트 컴프리헨션, lambda, map, reduce, filter**에 대해 정리해보려 한다.

<br>

## [코드 간결성2]
if/else 조건문은 한줄로 작성이 가능하다

#### programmers Level1 예제: Week8. 콜라츠
```
# 일반적인 코드
if num%==0:
  num = num / 2
else:
  num = num * 3 + 1
```

위의 코드는 다음과 같이 작성이 가능하다
```
num = num / 2 if num%2==0 else num * 3 + 1
```

<br>

## [변수명 작성 규칙]
사람들마다 변수명을 짓는 방식은 다양하게 나타나지만 사회적으로 공통된 표기방식들이 있다. **Camel case, Pascal case, Snake case, Kebab case**가 대표적인 표기 방법이다

<br>

## 📖 참고자료
1) [이코테 교재 강의](https://www.youtube.com/playlist?list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC)
2) [패스트캠퍼스 강의](https://fastcampus.co.kr/dev_online_algo)
3) [잔재미코딩](https://www.fun-coding.org/PL&OOP1-1.html)
