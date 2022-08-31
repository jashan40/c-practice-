#include <stdio.h>

int main() {
   int a;
   printf("enter any integer:");
   scanf("%d",&a);
   a%2==0 ? printf("%dis even",a):printf("%d is odd",a);

    return 0;
}
