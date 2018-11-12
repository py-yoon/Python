### Readme.md
깃허브에서 README.md 파일은 마크다운 형식으로 글이 작성된다. 그냥 쓰면 된다.

### 이 공간은 파이썬 테스트 위주로 올릴 계획

### 사인함수 그리기
```
import numpy as np
%matplotlib inline
import matplotlib.pyplot as plt
x=np.linspace(-5,5,100)
y=np.sin(x) # 함수를 바꾸어 cos(x), tan(x) 등도 가능하다.
plt.plot(x,y)
```

### X<

```
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
```
import turtle as t

n=100
t.bgcolor("black")
t.color("red")
t.speed(0)
for x in range(n):
    t.circle(100)
    t.left(3.6)
```
