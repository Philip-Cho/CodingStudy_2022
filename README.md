# CodingStudy_2022

## 1. 프로그래머스 코딩 스터디 문제 & 답안

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

## 실행시간 측정
코드가 전부 실행되는 시간을 체크할 수 있다. (시간단위: 초)

```
import time
start = time.time() # 코드 시작

# 코드 작성

end = time.time() - start
print(end)
```

<br>

## 📖 참고자료
1) [이코테 교재 강의](https://www.youtube.com/playlist?list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC)
2) [패스트캠퍼스 강의](https://fastcampus.co.kr/dev_online_algo)
3) [잔재미코딩](https://www.fun-coding.org/PL&OOP1-1.html)
