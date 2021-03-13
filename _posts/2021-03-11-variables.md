---
layout: posts
title: 변수 사용 방법
categories: 변수
toc: true
toc_sticky: true
toc_label: "페이지 주요 목차"
last_modified_at: 2021-03-12T08:06:00-05:00
---



### 1. 여러 변수에 동시에 다른 값 할당  
---
~~~
num1=34
num2=45
num3=56
~~~
~~~
num1=34; num2=45; num3=56
~~~
~~~
num1, num2, num3 = 34, 45, 56
~~~
위의 세 코드는 모두 같은 결과를 가집니다.


### 2. 여러 변수에 같은 값 할당
---
~~~
num1=0
num2=0
num3=0
~~~
~~~
num1, num2, num3 = 0, 0, 0
~~~
~~~
num1=num2=num3=0
~~~
위의 세 가지 방법으로 구현한 코드에서 세 변수는 모두 0의 값으로 초기화 됩니다.

***코드가 짧으면 논리 파악이 더 쉬워집니다!***

### 3. 세 변수의 값 교환
---
~~~
std1, std2, std3, temp = 'kim', 'lee', 'yun' , ''

temp = std1
std1 = std2
std2 = std3
std3 = temp
~~~
C언어나 Java언어는 값을 교환하기 위해 temp(임시) 변수가 필요하지만, 파이썬은 별도의 기억 장소가 필요하지 않습니다.

~~~
std1, std2, std3 = 'kim', 'lee', 'yun'
std1, std2, std3 = std2, std3, std1
~~~
파이썬은  변수의 값 교환이 직관적으로 이루어 집니다.

