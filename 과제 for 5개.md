```c
#include <stdio.h>

int main(void)
{
    // int i; //정수 i를 변수로 선언.
    for(int i=0; i<3; i++) //초기식, 조건식, 증감식
    {
        printf("나는 최고\n");
    }
    return 0;
}
```
```c
//for문의 반복을 이용한 합 구하기
#include <stdio.h>

int main(void)
{
    int sum; //sum은 정수들의 합을 저장하는 변수
    
    sum=0; //변수 sum을 0으로 초기화
    for(int i=1; i<=10; i++) // for문의 초기식에서 변수 i를 선언하고 1로 초기화, i는 1부터 10까지 증가
    {
        sum+=i; //sum=sum+i, 변수 sum의 값은 계속 증가하면서 변화함
    }
    printf("1부터 10까지의 정수의 합=%d\n",sum); //for문이 끝나면 실행, 화면에 sum 값이 출력

    return 0;
}
```


```c
#include <stdio.h>

int main(void)
{
    int i, j; //정수형 변수 i,j 선언

    for(i=0; i<5; i++) //바깥 반복문
    {
        for(j=0; j<5; j++) //안쪽 반복문
        {
            printf("*");
        }
        printf("\n"); //다음 행으로 넘어가기 위한 줄바꿈
    }
    return 0;
}

```
```c

#include <stdio.h>

int main(void)
{
    int i, j;

    for(i=1; i<=5; i++) 
    {
        for(j=1; j<=i; j++)
        {
            printf("%d",j); //j의 값을 출력
        }
        printf("\n"); //줄바꿈 
    }
    return 0;
}
```


```c
//직각삼각형 별찍기
#include <stdio.h>

int main(void)
{
    int i,j;

    for(i=0; i<5; i++)
    {
        for(j=0; j<=i; j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}


```
