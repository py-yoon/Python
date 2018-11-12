### Readme.md
깃허브에서 README.md 파일은 마크다운 형식으로 글이 작성된다. 그냥 쓰면 된다.

### 프로그래밍 언어
- [프로그래밍 Top10 언어 - 2018년](https://github.com/py-yoon/Python/wiki/Python!)
- 배우고 싶은 언어는 많으나 능력도 없고 시간도 부족. 가장 대중적이고 범용도 높은 파이썬을 공부할 계획.

### 이 공간은 파이썬 테스트 위주로 올릴 계획
- 기초적인 것부터 시작해 실용과 재미 위주로 작업.
- [파이썬 기초 문법](https://github.com/py-yoon/Python/wiki/%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EA%B8%B0%EC%B4%88-%EB%AC%B8%EB%B2%95)

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
plt.xlabel("x")
plt.ylabel("y")
plt.title("Y=X^2")
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
