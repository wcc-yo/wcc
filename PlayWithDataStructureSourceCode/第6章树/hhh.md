# 一
 1. 在屏幕上显示"HELLO WORLD!"
```C
#include <stdio.h>
int main()
{
printf("HELLO WRLD!");
return 0;//表返回值
}
```
2. 输入数据1+2=
``` C
#include <stdio.h>
int main()
{
int a,b,Sum;
a=1,b=2;
Sum=a+b;
printf("%d+%d=%d",a,b,Sum);
return 0;
}
```
3. 求任意两个数的最大值
``` C
#include <stdio.h>
int main()
{
 int a,b;//定义变量
 scanf("%d%d",&a,&b);//输入变量a,b
 if (a>b)
 printf("%d\n",a);
 else
 printf("%d\n",b);//if,else后无分号
 return 0;
}
```
4. 求任意三个数的最大值
 ```C
 #include <stdio.h>
 void main()//void表空
 {
 int a,b,c,d,Max;
 printf("请输入任意三个数:\n");
 scanf("%d,%d,%d",&a,&b,&c);
 if(a>b)
 d=a;
 else 
 d=b;
 if(d>c)
 Max=d;
 else
 Max=c;
 printf("Max=%d\n",Max);
 }