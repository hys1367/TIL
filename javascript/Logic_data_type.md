### 논리자료형
참(true)혹은 거짓(False)을 나타내는
자료형을 논리 자료형 이라고 한다.
###비교 연산자
숫자나 문자의 값을 비교하는 연산자
주어진 진술이 참이면 true, 거짓이면 False.
####예시
`print(3 > 5) # true`
`print(2 >=10) #False`

###비교 연산자의 종류
`== 같다`
`!= 다르다`
`> 왼쪽이 더 크다`
`< 오른쪽이 더 크다`
`>= 왼쪽이 같거나 크다`
`<= 오른쪽이 같거나 크다`
###논리 자료형의 연산
True. False밖에 없는 논리 자료형
 → 새로운 연산이 필요하다.
 #### 1. AND(모두 True니?)
 ###### 각 논리가 모두 True여야 True!
 `print(3==3 and 4>=5 and 6>2)`
 `#세 항이 모두 True이므로, True!`
 `>>> True
 #### 2. OR(True가 있니?)
 논리들 중 True가 존재하면 True!
 `print(3==4 or 4<=5 or 6<2)`
 `# 4<=5가 True이므로, True가 존재하기에 True!`
 `>>> True`
#### 3. NOT(기존의 논리와 반대로!)
논리값을 뒤집는다!
`print(not 3==4)`
`# False에 Not을 붙였으므로, True!`
`>>>True`
