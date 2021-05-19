---
layout: single
title: "조건문"
categories: 형성평가
toc: true
toc_sticky: true
toc_label: "페이지 주요 목차"
---

### 01. 사주보기
![saju](/assets/images/if1.jpg)
~~~c
#include <stdio.h>
~~~

### 02. 3개의 터널 통과
![tunnul](/assets/images/if2.jpg)
~~~c
#include <stdio.h>
 
int main(void)
{
   int tunnul_1, tunnul_2, tunnul_3;

   printf("세 터널의 높이를 차례대로 입력하세요 : ");
   scanf("%d,%d,%d",&tunnul_1,&tunnul_2,&tunnul_3);

   if(tunnul_1<=170)
     printf("충돌 %d", tunnul_1);
   else if(tunnul_2<=170)
     printf("충돌 %d", tunnul_2);
   else if(tunnul_3<=170)
     printf("충돌 %d", tunnul_3);
   else
     printf("무사 통과");
   return 0;
}
~~~

### 03. 이 달은 며칠까지 있을까?
![callenderl](/assets/images/if3.jpg)
~~~c

~~~
