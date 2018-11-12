## Python으로 놀기

### 프로그래밍 언어
- [프로그래밍 Top10 언어 - 2018년](https://github.com/py-yoon/Python/blob/master/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%88%9C%EC%9C%84.md)
- 배우고 싶은 언어는 많으나 능력도 없고 시간도 부족. 가장 대중적이고 범용도 높은 파이썬을 공부할 계획이다.

### 이 공간은 파이썬 테스트 위주로 올릴 계획
- 기초적인 것부터 시작해 실용과 재미 위주로 작업.
- [파이썬 기초 문법](https://github.com/py-yoon/Python/blob/master/%ED%8C%8C%EC%9D%B4%EC%8D%AC_%EA%B8%B0%EC%B4%88%EB%AC%B8%EB%B2%95.md)
- [함수는 뭐하는 거지?]

### 사인함수 그리기
```python
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt
x=np.linspace(-5,5,100)
y=np.sin(x) # 함수를 바꾸어 cos(x), tan(x) 등도 가능하다.
plt.plot(x,y)
```

### X의 제곱 

```python
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt
x=np.linspace(-10,10,100)
y=x**2
plt.xlabel("x") # x축 라벨 넣기
plt.ylabel("y") # y축 라벨 넣기
plt.title("Y=X^2") # 그래프 제목 넣기
plt.plot(x,y)
```

### 거북이로 그림 그리기
```python
import turtle as t

n=100
t.bgcolor("black")
t.color("red")
t.speed(0)
for x in range(n):
    t.circle(100)
    t.left(3.6)
```
