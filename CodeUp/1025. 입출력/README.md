# [CodeUp] 기초 입출력 - 1025 

[문제 링크](https://www.acmicpc.net/problem/10869) 

### 문제 설명

<p>다섯 자리의 정수 1개를 입력받아 각 자리별로 나누어 출력한다.
</p>

### 입력 

 <p>다섯 자리로 이루어진 1개의 정수를 입력받는다.
(단, 10,000 <= 입력받는 수 <= 99,999 )</p>

### 출력 

 <p>각 자리의 숫자를 분리해 한 줄에 하나씩 [ ]속에 넣어 출력한다.
</p>

### 후기
정말 어려웠다... 아직 논리적으로 생각하는 능력이 부족하다는걸 깨달았다.

```java
for(int i = 0; i < arr.length; i++) 
== 
for(int i : arr)
```
이 코드가 배열에서 가져올 값이 없을 때까지 값을 가져오는 명령문이다. 앞으로 자주 사용하게 될 것 같다. 

```java
for (int j = arr.length -1; j > i; j--) {
                System.out.print("0");
            }
```
for(초기화; 조건식; 반복문)
위 코드를 해석해보면
```
j = 4로 초기화하고 j가 i보다 클 때까지 반복한다. 1회 반복할 때마다 "0"을 출력하고 반복 횟수는 1씩 줄어든다.
```
라고 볼 수 있다. 
다음에 for문을 사용하는 문제가 나오면 잘 사용해 봐야겠다...

