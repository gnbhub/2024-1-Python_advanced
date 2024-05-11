| 작성자  |   날짜   | 언어    |
| ------- | --------- | ------- |
| Name    | YY.MM.DD  | Python  |

# Problem_Title

 
 - https://www.acmicpc.net/source/75989066
  

### 풀이 과정  



### 소스 코드

```Language
bg=[]
for i in range(101):
  for j in range(101):
    bg.append([j,i])

N=int(input())
for _ in range(N):
  X,Y=map(int,input().split())
  for x in range(X,X+10):
    for y in range(Y,Y+10):
      bg[x+y*101]=1  
print(bg.count(1))
```

### 결과 화면
