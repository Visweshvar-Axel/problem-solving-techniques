# problem-solving-techniques
<div>#include <stdio.h>
int fact(int n){
    if(n<=0)return 1;
    return n*fact(n-1);
}
int fib(int n){
    if(n<=0)return 0;
    else if(n==1)return 1;
    return fib(n-1)+fib(n-2);
}
int main()
{
    printf("%d",fact(5));
    for (int i = 0; i < 10; i++) {
        printf("\n%d",fib(i));
    }

    return 0;
}
</div>
