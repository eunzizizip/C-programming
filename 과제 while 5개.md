```c
#include <stdio.h>

int main(void)
{
    int i=0;

    while(i<3)
    {
        printf("나는 최고\n");
        i++;
    }
    return 0;
}
```

```c
#include <stdio.h>

int main(void)
{
    int i, sum;
    i=1;
    sum=0;

    while(i<=10)
    {
        sum+=i;
        i++;
    }
    printf("1부터 10까지의 정수의 합=%d\n",sum);
    return 0;
}
```

```c
#include <stdio.h>

int main(void)
{
    int i=0;
    int j=0;

    while(i<5)
    {
        j=0;
       while(j<5) 
       {
        printf("*");
        j++;
       }
        i++;
       printf("\n");
    }
    return 0;
}
```

```c
#include <stdio.h>

int main(void)
{
    int i=1;
    int j=1;

    while(i<=5)
    {
        j=1;
        while(j<=i)
        {
            printf("%d",j);
            j++;
        }
        i++;
        printf("\n");
    }
    return 0;
}
```

```c
#include <stdio.h>

int main(void)
{
   int i=0;
   int j=0;

   while(i<5)
   {
    j=0;
    while(j<=i)
    {
        printf("*");
        j++;
    }
    i++;
    printf("\n");
   }
   return 0;
}
```
